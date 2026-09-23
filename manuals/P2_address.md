The address gap on the Sun-2 P2 private memory bus is caused by **hardware address multiplexing** designed to directly drive Dynamic RAM (DRAM) chips while saving physical pins on the VME/Multibus backplane.

&nbsp;

Instead of putting address multiplexers on every single memory expansion card, Sun placed the multiplexing logic on the CPU board. The CPU splits the Motorola 68010's flat memory address and sequences it across the P2 bus to match the Row Address Strobe (RAS) and Column Address Strobe (CAS) timing required by DRAM.

&nbsp;

Here is exactly how the math and pin routing works out for a 1MB memory board:

**1\. The Multiplexed Lines (A1 through A9)**

The 68010 uses a 16-bit data bus, meaning memory is accessed in 2-byte words. Therefore, A0 is implied by the Upper/Lower Data Strobe (UDS/LDS) signals, and word addressing begins at A1.

* During the **RAS phase**, the CPU board drives address bits **A1 through A9** onto these 9 physical bus lines.  
* During the **CAS phase**, the CPU board drives address bits **A10 through A18** onto those exact same 9 physical bus lines.

This is why there are no physical traces for A10 through A17 on the P2 connector—they share the lines with A1–A8.

&nbsp;

**2\. The 1MB Board Architecture & Bank Selection**

Standard 1MB Sun-2 memory boards of that era typically utilized two banks of 256Kbit (or eight banks of 64Kbit) DRAM chips.

* 9 multiplexed address lines yield 18 bits of addressing space per bank.  
* $2^{18}$ words \= 256K words \= **512 KB per bank**.  
* To get 1MB, the board needs two 512KB banks.

&nbsp;

**3\. The Unmultiplexed High-Order Lines (A18 through A21)**

Because a 1MB board has multiple 512KB banks, and the system can hold multiple 1MB boards, the memory cards need to know *immediately* at the start of a bus cycle whether they are the target of the memory access, and which local bank to activate.

* **A18** is the 512KB boundary bit. It is sent unmultiplexed on the bus so the memory board's local logic can use it immediately as a **Bank Select** signal.  
* **A19, A20, and A21** are used for **Board Select**. They feed into the memory board's address decoding logic (often compared against DIP switches or jumpers on the board) to determine if the board should wake up and accept the incoming RAS/CAS signals from A1-A9.

&nbsp;

By removing A10–A17 from the backplane, Sun eliminated 8 unnecessary pins and removed the need for multiplexer ICs (like 74F257s) on every single memory card, significantly simplifying the memory board schematics and reducing signal routing congestion.

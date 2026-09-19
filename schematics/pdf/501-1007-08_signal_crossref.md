# Sun-2 CPU Board (501-1007-08) — Master Signal Cross-Reference

## Overview

- **Document:** Sun-2 CPU Board Schematic (`501-1007-08`, 9 pages)
- **Total Unique Verified Signals:** **390**
- **Signals Appearing Across Multiple Pages:** **252**
- **Signals Appearing on Single Page Only:** **138**
- **Total Signal Annotations Placed in PDF:** **1325**

Annotated schematic PDF: [501-1007-08_annotated.pdf](file:///Users/dmoisa/Documents/PCBs/sun2_cpu/schematics/pdf/501-1007-08_annotated.pdf)

### Page Index

| Page | Section Description | Unique Signals | Total Instances |
|:----:|:-------------------|:--------------:|:---------------:|
| Page 1 | 68010 CPU, Power-On Reset, DTACK Generator, Bus Error (BERR) Logic, Interrupt Priority Encoder | 94 | 142 |
| Page 2 | System Clock Generator, Timeout Counter, Timer Controller, Refresh Counter, DVMA Controller & Decoder | 59 | 81 |
| Page 3 | MMU Context Register, Segment Map, Page Map, Protection Decoder, Statistics Bit Logic | 104 | 233 |
| Page 4 | Strobe Decoders, Boot PROMs, Real-Time Clock (RTC), ID PROM, Bus Error Register, System Enable Register | 81 | 139 |
| Page 5 | Rasterop Processor (ROP), Parity Check/Generation Logic, P2-Bus Interface | 124 | 187 |
| Page 6 | Floating-Point Processor (80287 FPP), Data Cipher Processor (Am9518 DCP), System Timer (Am9513), Dual Serial Controller (Z8530 SCC), RS423 Drivers | 76 | 139 |
| Page 7 | Multibus (P1) Address Out, Address In, Data Buffers, Bus Arbiter (8289) | 118 | 173 |
| Page 8 | Diagnostic Register, Diagnostic Input Port, Multibus P1 Connector (P86), Sun P2 Connector (P60), Serial DB Connectors | 177 | 231 |
| Page 9 | Power Distribution & Bypass Capacitors | 0 | 0 |

---

## Master Alphabetical Signal Cross-Reference

| Signal Name | Pages Appearing | Signal Family / Subsystem Description |
|:------------|:---------------:|:--------------------------------------|
| `ABCS` | 7 | CPU Control & Bus Cycle Timing Strobe |
| `ACC` | 3 | CPU Control & Bus Cycle Timing Strobe |
| `AEN\` | 2, 4, 7 | CPU Control & Bus Cycle Timing Strobe |
| `AS\` | 1, 5, 6 | CPU Control & Bus Cycle Timing Strobe |
| `AUX0` | 6 | Math (80287) / System Timer Subsystem |
| `AUX1` | 6 | Math (80287) / System Timer Subsystem |
| `AUX2` | 6 | Math (80287) / System Timer Subsystem |
| `AUX3` | 6 | Math (80287) / System Timer Subsystem |
| `AUX4` | 6 | Math (80287) / System Timer Subsystem |
| `AUX5` | 6 | Math (80287) / System Timer Subsystem |
| `AUX7` | 6 | Math (80287) / System Timer Subsystem |
| `BEN\` | 2, 7 | CPU Control & Bus Cycle Timing Strobe |
| `BERR\` | 1 | CPU Control & Bus Cycle Timing Strobe |
| `BG\` | 1 | CPU Control & Bus Cycle Timing Strobe |
| `BOOTEN\` | 3, 4 | CPU Control & Bus Cycle Timing Strobe |
| `BOOT\` | 4 | CPU Control & Bus Cycle Timing Strobe |
| `BPRN\` | 7 | CPU Control & Bus Cycle Timing Strobe |
| `BREQ\` | 7 | CPU Control & Bus Cycle Timing Strobe |
| `BR\` | 1 | CPU Control & Bus Cycle Timing Strobe |
| `C.S3` | 2, 5, 7 | Decoded Chip Select |
| `C.S3\` | 2, 5 | Decoded Chip Select |
| `C.S4` | 1, 7 | Decoded Chip Select |
| `C.S4\` | 2, 4, 5 | Decoded Chip Select |
| `C.S5` | 1, 2, 3, 4 | Decoded Chip Select |
| `C.S5\` | 2 | Decoded Chip Select |
| `C.S6` | 2 | Decoded Chip Select |
| `C.S6\` | 2, 3, 7 | Decoded Chip Select |
| `C.S7` | 2, 5, 6 | Decoded Chip Select |
| `C.S7\` | 2 | Decoded Chip Select |
| `CE.BYTE\` | 2, 7 | CPU Control & Bus Cycle Timing Strobe |
| `CE.WORD\` | 2, 7 | CPU Control & Bus Cycle Timing Strobe |
| `CLK` | 1, 6, 7 | CPU Control & Bus Cycle Timing Strobe |
| `CTSA\` | 6 | Serial Interface (SCC / RS423) |
| `CTSB\` | 6, 8 | Serial Interface (SCC / RS423) |
| `CXS0` | 3 | MMU Context Register |
| `CXS1` | 3 | MMU Context Register |
| `CXS2` | 3 | MMU Context Register |
| `CXS3` | 3 | MMU Context Register |
| `CXU0` | 3 | MMU Context Register |
| `CXU1` | 3 | MMU Context Register |
| `CXU2` | 3 | MMU Context Register |
| `CXU3` | 3 | MMU Context Register |
| `DCDA\` | 6 | Serial Interface (SCC / RS423) |
| `DCDB\` | 6, 8 | Serial Interface (SCC / RS423) |
| `DIS.D\` | 5 | CPU Control & Bus Cycle Timing Strobe |
| `DIS\` | 2, 3, 5 | CPU Control & Bus Cycle Timing Strobe |
| `DSRA\` | 6 | Serial Interface (SCC / RS423) |
| `DSRB\` | 6, 8 | Serial Interface (SCC / RS423) |
| `DS\` | 1, 3, 4, 5, 6 | CPU Control & Bus Cycle Timing Strobe |
| `DTRA\` | 6, 8 | Serial Interface (SCC / RS423) |
| `DTRB\` | 6, 8 | Serial Interface (SCC / RS423) |
| `EN.DVMA` | 2, 4 | Subsystem Enable / Control |
| `EN.INT` | 1, 4 | Subsystem Enable / Control |
| `EN.INT1` | 1, 4 | Subsystem Enable / Control |
| `EN.INT2` | 1, 4 | Subsystem Enable / Control |
| `EN.INT3` | 1, 4 | Subsystem Enable / Control |
| `EN.PARERR\` | 4, 5 | Subsystem Enable / Control |
| `EN.PARGEN` | 4, 5 | Subsystem Enable / Control |
| `EN.PARGEN\` | 1, 5 | Subsystem Enable / Control |
| `EN.S4\` | 1, 2 | Subsystem Enable / Control |
| `ENVEE` | 6 | CPU Control & Bus Cycle Timing Strobe |
| `FOUT` | 6 | Math (80287) / System Timer Subsystem |
| `FPPERR\` | 1, 6 | CPU Control & Bus Cycle Timing Strobe |
| `HALT\` | 1 | CPU Control & Bus Cycle Timing Strobe |
| `IA16` | 3 | MMU Intermediate Address (Segment) |
| `IA17` | 3 | MMU Intermediate Address (Segment) |
| `IA18` | 3 | MMU Intermediate Address (Segment) |
| `IA19` | 3 | MMU Intermediate Address (Segment) |
| `IA20` | 3 | MMU Intermediate Address (Segment) |
| `IA21` | 3 | MMU Intermediate Address (Segment) |
| `IA22` | 3 | MMU Intermediate Address (Segment) |
| `IA23` | 3 | MMU Intermediate Address (Segment) |
| `IN0` | 8 | Diagnostic Input Configuration Port |
| `IN1` | 8 | Diagnostic Input Configuration Port |
| `IN10` | 8 | Diagnostic Input Configuration Port |
| `IN11` | 8 | Diagnostic Input Configuration Port |
| `IN12` | 8 | Diagnostic Input Configuration Port |
| `IN13` | 8 | Diagnostic Input Configuration Port |
| `IN14` | 8 | Diagnostic Input Configuration Port |
| `IN15` | 8 | Diagnostic Input Configuration Port |
| `IN2` | 4, 8 | Diagnostic Input Configuration Port |
| `IN3` | 8 | Diagnostic Input Configuration Port |
| `IN4` | 8 | Diagnostic Input Configuration Port |
| `IN5` | 8 | Diagnostic Input Configuration Port |
| `IN7` | 8 | Diagnostic Input Configuration Port |
| `IN8` | 8 | Diagnostic Input Configuration Port |
| `IN9` | 8 | Diagnostic Input Configuration Port |
| `INIT\` | 1, 2, 4, 7 | Diagnostic Input Configuration Port |
| `INT.SCC\` | 1, 6 | Interrupt Request Priority Line |
| `INT1\` | 1, 8 | Interrupt Request Priority Line |
| `INT2\` | 1, 8 | Interrupt Request Priority Line |
| `INT3\` | 1, 8 | Interrupt Request Priority Line |
| `INT4\` | 1, 8 | Interrupt Request Priority Line |
| `INT5\` | 1, 6, 8 | Interrupt Request Priority Line |
| `INT6\` | 1, 8 | Interrupt Request Priority Line |
| `INT7\` | 6 | Interrupt Request Priority Line |
| `IOACK\` | 1, 6 | CPU Control & Bus Cycle Timing Strobe |
| `IOB\` | 7 | CPU Control & Bus Cycle Timing Strobe |
| `LD.DST\` | 5 | CPU Control & Bus Cycle Timing Strobe |
| `LD.SRC\` | 5 | CPU Control & Bus Cycle Timing Strobe |
| `LDS\` | 1 | CPU Control & Bus Cycle Timing Strobe |
| `LED0` | 8 | Diagnostic Status LED Indicator |
| `LED1` | 8 | Diagnostic Status LED Indicator |
| `LED2` | 8 | Diagnostic Status LED Indicator |
| `LED3` | 8 | Diagnostic Status LED Indicator |
| `LED4` | 8 | Diagnostic Status LED Indicator |
| `LED5` | 8 | Diagnostic Status LED Indicator |
| `LED6` | 8 | Diagnostic Status LED Indicator |
| `LED7` | 8 | Diagnostic Status LED Indicator |
| `MA11` | 3, 4, 5, 7 | MMU Memory Address (Physical Page) |
| `MA12` | 3, 4, 5, 7 | MMU Memory Address (Physical Page) |
| `MA13` | 3, 4, 5, 7 | MMU Memory Address (Physical Page) |
| `MA14` | 3, 4, 5, 7 | MMU Memory Address (Physical Page) |
| `MA15` | 3, 5, 7 | MMU Memory Address (Physical Page) |
| `MA16` | 3, 5, 7 | MMU Memory Address (Physical Page) |
| `MA17` | 3, 5, 7 | MMU Memory Address (Physical Page) |
| `MA18` | 3, 5, 7 | MMU Memory Address (Physical Page) |
| `MA19` | 3, 5, 7 | MMU Memory Address (Physical Page) |
| `MA20` | 3, 5 | MMU Memory Address (Physical Page) |
| `MA21` | 3, 5 | MMU Memory Address (Physical Page) |
| `MA22` | 3, 5 | MMU Memory Address (Physical Page) |
| `MOD` | 3 | CPU Control & Bus Cycle Timing Strobe |
| `OE.ROP\` | 1, 5 | CPU Control & Bus Cycle Timing Strobe |
| `P.A1` | 1, 2, 3, 4, 5, 6, 7 | 68010 Processor Bus |
| `P.A10` | 1, 2, 4, 5, 7 | 68010 Processor Bus |
| `P.A11` | 1, 3, 4, 7 | 68010 Processor Bus |
| `P.A12` | 1, 3, 4, 7 | 68010 Processor Bus |
| `P.A13` | 1, 3, 4, 7 | 68010 Processor Bus |
| `P.A14` | 1, 3, 4, 7 | 68010 Processor Bus |
| `P.A15` | 1, 3, 4, 7 | 68010 Processor Bus |
| `P.A16` | 1, 3, 7 | 68010 Processor Bus |
| `P.A17` | 1, 7 | 68010 Processor Bus |
| `P.A18` | 1, 3, 7 | 68010 Processor Bus |
| `P.A19` | 1, 3, 7 | 68010 Processor Bus |
| `P.A2` | 1, 2, 3, 4, 5, 6, 7 | 68010 Processor Bus |
| `P.A20` | 1, 3, 7 | 68010 Processor Bus |
| `P.A21` | 1, 3, 7 | 68010 Processor Bus |
| `P.A22` | 1, 3, 7 | 68010 Processor Bus |
| `P.A23` | 1, 3, 7 | 68010 Processor Bus |
| `P.A3` | 1, 2, 3, 4, 5, 7 | 68010 Processor Bus |
| `P.A4` | 1, 2, 4, 5, 7 | 68010 Processor Bus |
| `P.A5` | 1, 2, 4, 5, 7 | 68010 Processor Bus |
| `P.A6` | 1, 2, 4, 5, 7 | 68010 Processor Bus |
| `P.A7` | 1, 2, 4, 7 | 68010 Processor Bus |
| `P.A8` | 1, 2, 4, 5, 7 | 68010 Processor Bus |
| `P.A9` | 1, 2, 4, 5, 7 | 68010 Processor Bus |
| `P.AS\` | 1, 2, 3, 5 | 68010 Processor Bus |
| `P.BACK\` | 1, 2, 3 | 68010 Processor Bus |
| `P.BERR\` | 1 | 68010 Processor Bus |
| `P.BG\` | 1, 2 | 68010 Processor Bus |
| `P.BR\` | 1, 2 | 68010 Processor Bus |
| `P.D0` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D1` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D10` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D11` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D12` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D13` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D14` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D15` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D2` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D3` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D4` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D5` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D6` | 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D7` | 1, 3, 4, 5, 6, 8 | 68010 Processor Bus |
| `P.D8` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.D9` | 1, 3, 4, 5, 6, 7, 8 | 68010 Processor Bus |
| `P.DTACK\` | 1 | 68010 Processor Bus |
| `P.FC0` | 1, 3 | 68010 Processor Bus |
| `P.FC1` | 1, 2, 3 | 68010 Processor Bus |
| `P.FC2` | 1, 3, 5, 6, 7 | 68010 Processor Bus |
| `P.HALT\` | 1, 2, 8 | 68010 Processor Bus |
| `P.LDS\` | 1, 2, 5, 7 | 68010 Processor Bus |
| `P.MMU\` | 3 | 68010 Processor Bus |
| `P.R/W\` | 1, 2, 3, 6 | 68010 Processor Bus |
| `P.RESET\` | 1, 5, 8 | 68010 Processor Bus |
| `P.SPROG\` | 3, 4 | 68010 Processor Bus |
| `P.UDS\` | 1, 2, 5 | 68010 Processor Bus |
| `P.VPA\` | 1, 4 | 68010 Processor Bus |
| `P1.A0\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A10\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A11\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A12\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A13\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A14\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A15\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A16\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A17\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A18\` | 2, 7, 8 | Multibus (P1) Bus Interface |
| `P1.A19\` | 2, 7, 8 | Multibus (P1) Bus Interface |
| `P1.A1\` | 2, 7, 8 | Multibus (P1) Bus Interface |
| `P1.A2\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A3\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A4\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A5\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A6\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A7\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A8\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.A9\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.AACK\` | 8 | Multibus (P1) Bus Interface |
| `P1.BCLK\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.BHEN\` | 2, 7, 8 | Multibus (P1) Bus Interface |
| `P1.BPRN\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.BPRO\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.BREQ\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.BUSY\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.CBRQ\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.CCLK\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D0\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D10\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D11\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D12\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D13\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D14\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D15\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D1\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D2\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D3\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D4\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D5\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D6\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D7\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D8\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.D9\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.INH1\` | 8 | Multibus (P1) Bus Interface |
| `P1.INH2\` | 8 | Multibus (P1) Bus Interface |
| `P1.INIT\` | 1, 7, 8 | Multibus (P1) Bus Interface |
| `P1.INT0\` | 8 | Multibus (P1) Bus Interface |
| `P1.INT1\` | 8 | Multibus (P1) Bus Interface |
| `P1.INT2\` | 8 | Multibus (P1) Bus Interface |
| `P1.INT3\` | 8 | Multibus (P1) Bus Interface |
| `P1.INT4\` | 8 | Multibus (P1) Bus Interface |
| `P1.INT5\` | 8 | Multibus (P1) Bus Interface |
| `P1.INT6\` | 8 | Multibus (P1) Bus Interface |
| `P1.INT7\` | 8 | Multibus (P1) Bus Interface |
| `P1.INTA\` | 8 | Multibus (P1) Bus Interface |
| `P1.IORC\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.IOWC\` | 7, 8 | Multibus (P1) Bus Interface |
| `P1.MRDC\` | 2, 7, 8 | Multibus (P1) Bus Interface |
| `P1.MWTC\` | 2, 7, 8 | Multibus (P1) Bus Interface |
| `P1.XACK\` | 2, 8 | Multibus (P1) Bus Interface |
| `P1TOP` | 2, 7 | CPU Control & Bus Cycle Timing Strobe |
| `P2.A01` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A02` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A03` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A04` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A05` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A06` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A07` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A08` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A09` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A18` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A19` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A20` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A21` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.A22` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.CAS\` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI0` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI1` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI10` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI11` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI12` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI13` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI14` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI15` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI2` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI3` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI4` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI5` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI6` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI7` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI8` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DI9` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DIL` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DIU` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO0` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO1` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO10` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO11` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO12` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO13` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO14` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO15` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO2` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO3` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO4` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO5` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO6` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO7` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO8` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DO9` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DOL` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.DOU` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.R/W\` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.RAS\` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.WAIT\` | 1, 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.WEL\` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `P2.WEU\` | 5, 8 | Sun Memory (P2) High-Speed Bus |
| `PARERRL\` | 1, 4, 5 | CPU Control & Bus Cycle Timing Strobe |
| `PARERRU\` | 1, 4, 5 | CPU Control & Bus Cycle Timing Strobe |
| `PCLK` | 6 | Math (80287) / System Timer Subsystem |
| `POR\` | 1, 2, 4, 8 | CPU Control & Bus Cycle Timing Strobe |
| `PROT0` | 3 | MMU Page Protection Attribute |
| `PROT1` | 3 | MMU Page Protection Attribute |
| `PROT2` | 3 | MMU Page Protection Attribute |
| `PROT3` | 3 | MMU Page Protection Attribute |
| `PROT4` | 3 | MMU Page Protection Attribute |
| `PROT5` | 3 | MMU Page Protection Attribute |
| `PROTERR\` | 1, 2, 3, 4 | MMU Page Protection Attribute |
| `Q.AS\` | 1, 2, 7 | CPU Control & Bus Cycle Timing Strobe |
| `RD.CXL\` | 3 | Decoded Read Strobe |
| `RD.CXU\` | 3 | Decoded Read Strobe |
| `RD.DCP\` | 4, 6 | Decoded Read Strobe |
| `RD.ENABLE\` | 3, 4 | Decoded Read Strobe |
| `RD.ERROR\` | 3, 4 | Decoded Read Strobe |
| `RD.FPP\` | 4, 6 | Decoded Read Strobe |
| `RD.IDPROM\` | 3, 4 | Decoded Read Strobe |
| `RD.IO\` | 4 | Decoded Read Strobe |
| `RD.PMAP0L\` | 3 | Decoded Read Strobe |
| `RD.PMAP0U\` | 3 | Decoded Read Strobe |
| `RD.PMAP1L\` | 3 | Decoded Read Strobe |
| `RD.PMAP1U\` | 3 | Decoded Read Strobe |
| `RD.PORT\` | 4, 8 | Decoded Read Strobe |
| `RD.PROM\` | 4 | Decoded Read Strobe |
| `RD.RAM\` | 4, 5 | Decoded Read Strobe |
| `RD.ROP\` | 4, 5 | Decoded Read Strobe |
| `RD.RTC\` | 4 | Decoded Read Strobe |
| `RD.SCC\` | 4, 6 | Decoded Read Strobe |
| `RD.SMAP\` | 3 | Decoded Read Strobe |
| `RD.TIMER\` | 4, 6 | Decoded Read Strobe |
| `REN\` | 2, 8 | CPU Control & Bus Cycle Timing Strobe |
| `ROPCYC\` | 1, 5 | Rasterop Processor Control |
| `ROPST0` | 5 | Rasterop Processor Control |
| `ROPST1` | 5 | Rasterop Processor Control |
| `ROPST2` | 5 | Rasterop Processor Control |
| `RREQ\` | 2, 7 | CPU Control & Bus Cycle Timing Strobe |
| `RTSA\` | 6 | Serial Interface (SCC / RS423) |
| `RTSB\` | 6, 8 | Serial Interface (SCC / RS423) |
| `RXCA\` | 6 | Serial Interface (SCC / RS423) |
| `RXCB\` | 6 | Serial Interface (SCC / RS423) |
| `RXDA` | 6 | Serial Interface (SCC / RS423) |
| `RXDB` | 6 | Serial Interface (SCC / RS423) |
| `SACK\` | 2 | CPU Control & Bus Cycle Timing Strobe |
| `SAS\` | 2 | CPU Control & Bus Cycle Timing Strobe |
| `SBI\` | 4 | CPU Control & Bus Cycle Timing Strobe |
| `SDS\` | 2, 6 | CPU Control & Bus Cycle Timing Strobe |
| `SP0` | 6 | Math (80287) / System Timer Subsystem |
| `SP1` | 6 | Math (80287) / System Timer Subsystem |
| `SP2` | 6 | Math (80287) / System Timer Subsystem |
| `SP3` | 6 | Math (80287) / System Timer Subsystem |
| `SP4` | 6 | Math (80287) / System Timer Subsystem |
| `SP5` | 6 | Math (80287) / System Timer Subsystem |
| `SP6` | 6 | Math (80287) / System Timer Subsystem |
| `SP7` | 6 | Math (80287) / System Timer Subsystem |
| `SYSB` | 2, 5, 7 | CPU Control & Bus Cycle Timing Strobe |
| `TIMEOUT\` | 1, 2, 4 | CPU Control & Bus Cycle Timing Strobe |
| `TXCA\` | 6 | Serial Interface (SCC / RS423) |
| `TXCB\` | 6 | Serial Interface (SCC / RS423) |
| `TXDA` | 6 | Serial Interface (SCC / RS423) |
| `TXDB` | 6 | Serial Interface (SCC / RS423) |
| `TYPE0` | 1, 3 | CPU Control & Bus Cycle Timing Strobe |
| `TYPE1` | 1, 3, 4, 7 | CPU Control & Bus Cycle Timing Strobe |
| `UDS\` | 1 | CPU Control & Bus Cycle Timing Strobe |
| `VALID` | 2, 3 | CPU Control & Bus Cycle Timing Strobe |
| `VEEA` | 6, 8 | CPU Control & Bus Cycle Timing Strobe |
| `VEEB` | 6, 8 | CPU Control & Bus Cycle Timing Strobe |
| `WR.CXL\` | 3 | Decoded Write Strobe |
| `WR.CXU\` | 3 | Decoded Write Strobe |
| `WR.DCP\` | 4, 6 | Decoded Write Strobe |
| `WR.DIAG\` | 3, 8 | Decoded Write Strobe |
| `WR.ENABLE\` | 3, 4 | Decoded Write Strobe |
| `WR.FPP\` | 4, 6 | Decoded Write Strobe |
| `WR.IO\` | 4 | Decoded Write Strobe |
| `WR.M\` | 5 | Decoded Write Strobe |
| `WR.PMAP0L\` | 3 | Decoded Write Strobe |
| `WR.PMAP0U\` | 3 | Decoded Write Strobe |
| `WR.PMAP0X\` | 3 | Decoded Write Strobe |
| `WR.PMAP1L\` | 3 | Decoded Write Strobe |
| `WR.PMAP1U\` | 3 | Decoded Write Strobe |
| `WR.RAM\` | 4, 5 | Decoded Write Strobe |
| `WR.ROP\` | 4, 5 | Decoded Write Strobe |
| `WR.RTC\` | 4 | Decoded Write Strobe |
| `WR.SCC\` | 4, 6 | Decoded Write Strobe |
| `WR.SMAP\` | 3 | Decoded Write Strobe |
| `WR.TIMER\` | 4, 6 | Decoded Write Strobe |
| `XACK\` | 1, 7 | CPU Control & Bus Cycle Timing Strobe |
| `XBERR\` | 1, 2 | CPU Control & Bus Cycle Timing Strobe |
| `XEN\` | 2, 7 | CPU Control & Bus Cycle Timing Strobe |
| `XHALT\` | 2 | CPU Control & Bus Cycle Timing Strobe |
| `XREQ\` | 2 | CPU Control & Bus Cycle Timing Strobe |

---

## Signals Grouped by Page

### Page 1: 68010 CPU, Power-On Reset, DTACK Generator, Bus Error (BERR) Logic, Interrupt Priority Encoder

**94 unique signals (142 instances):**

| Signal | Instances on Page | Also Appears On Pages |
|:-------|:-----------------:|:----------------------|
| `AS\` | 2 | 5, 6 |
| `BERR\` | 2 | *(Page 1 only)* |
| `BG\` | 1 | *(Page 1 only)* |
| `BR\` | 1 | *(Page 1 only)* |
| `C.S4` | 1 | 7 |
| `C.S5` | 1 | 2, 3, 4 |
| `CLK` | 1 | 6, 7 |
| `DS\` | 1 | 3, 4, 5, 6 |
| `EN.INT` | 1 | 4 |
| `EN.INT1` | 1 | 4 |
| `EN.INT2` | 1 | 4 |
| `EN.INT3` | 1 | 4 |
| `EN.PARGEN\` | 1 | 5 |
| `EN.S4\` | 1 | 2 |
| `FPPERR\` | 2 | 6 |
| `HALT\` | 2 | *(Page 1 only)* |
| `INIT\` | 1 | 2, 4, 7 |
| `INT.SCC\` | 2 | 6 |
| `INT1\` | 4 | 8 |
| `INT2\` | 5 | 8 |
| `INT3\` | 3 | 8 |
| `INT4\` | 2 | 8 |
| `INT5\` | 2 | 6, 8 |
| `INT6\` | 3 | 8 |
| `IOACK\` | 1 | 6 |
| `LDS\` | 1 | *(Page 1 only)* |
| `OE.ROP\` | 1 | 5 |
| `P.A1` | 1 | 2, 3, 4, 5, 6, 7 |
| `P.A10` | 1 | 2, 4, 5, 7 |
| `P.A11` | 2 | 3, 4, 7 |
| `P.A12` | 2 | 3, 4, 7 |
| `P.A13` | 2 | 3, 4, 7 |
| `P.A14` | 2 | 3, 4, 7 |
| `P.A15` | 2 | 3, 4, 7 |
| `P.A16` | 2 | 3, 7 |
| `P.A17` | 2 | 7 |
| `P.A18` | 2 | 3, 7 |
| `P.A19` | 2 | 3, 7 |
| `P.A2` | 1 | 2, 3, 4, 5, 6, 7 |
| `P.A20` | 2 | 3, 7 |
| `P.A21` | 2 | 3, 7 |
| `P.A22` | 2 | 3, 7 |
| `P.A23` | 2 | 3, 7 |
| `P.A3` | 1 | 2, 3, 4, 5, 7 |
| `P.A4` | 1 | 2, 4, 5, 7 |
| `P.A5` | 1 | 2, 4, 5, 7 |
| `P.A6` | 1 | 2, 4, 5, 7 |
| `P.A7` | 1 | 2, 4, 7 |
| `P.A8` | 1 | 2, 4, 5, 7 |
| `P.A9` | 1 | 2, 4, 5, 7 |
| `P.AS\` | 3 | 2, 3, 5 |
| `P.BACK\` | 3 | 2, 3 |
| `P.BERR\` | 1 | *(Page 1 only)* |
| `P.BG\` | 2 | 2 |
| `P.BR\` | 1 | 2 |
| `P.D0` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D1` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D10` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D11` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D12` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D13` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D14` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D15` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D2` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D3` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D4` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D5` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D7` | 1 | 3, 4, 5, 6, 8 |
| `P.D8` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.D9` | 1 | 3, 4, 5, 6, 7, 8 |
| `P.DTACK\` | 3 | *(Page 1 only)* |
| `P.FC0` | 2 | 3 |
| `P.FC1` | 2 | 2, 3 |
| `P.FC2` | 2 | 3, 5, 6, 7 |
| `P.HALT\` | 2 | 2, 8 |
| `P.LDS\` | 2 | 2, 5, 7 |
| `P.R/W\` | 2 | 2, 3, 6 |
| `P.RESET\` | 3 | 5, 8 |
| `P.UDS\` | 2 | 2, 5 |
| `P.VPA\` | 1 | 4 |
| `P1.INIT\` | 1 | 7, 8 |
| `P2.WAIT\` | 1 | 5, 8 |
| `PARERRL\` | 1 | 4, 5 |
| `PARERRU\` | 1 | 4, 5 |
| `POR\` | 2 | 2, 4, 8 |
| `PROTERR\` | 1 | 2, 3, 4 |
| `Q.AS\` | 1 | 2, 7 |
| `ROPCYC\` | 1 | 5 |
| `TIMEOUT\` | 1 | 2, 4 |
| `TYPE0` | 1 | 3 |
| `TYPE1` | 1 | 3, 4, 7 |
| `UDS\` | 1 | *(Page 1 only)* |
| `XACK\` | 1 | 7 |
| `XBERR\` | 1 | 2 |

### Page 2: System Clock Generator, Timeout Counter, Timer Controller, Refresh Counter, DVMA Controller & Decoder

**59 unique signals (81 instances):**

| Signal | Instances on Page | Also Appears On Pages |
|:-------|:-----------------:|:----------------------|
| `AEN\` | 1 | 4, 7 |
| `BEN\` | 1 | 7 |
| `C.S3` | 2 | 5, 7 |
| `C.S3\` | 1 | 5 |
| `C.S4\` | 2 | 4, 5 |
| `C.S5` | 1 | 1, 3, 4 |
| `C.S5\` | 1 | *(Page 2 only)* |
| `C.S6` | 1 | *(Page 2 only)* |
| `C.S6\` | 1 | 3, 7 |
| `C.S7` | 2 | 5, 6 |
| `C.S7\` | 1 | *(Page 2 only)* |
| `CE.BYTE\` | 1 | 7 |
| `CE.WORD\` | 1 | 7 |
| `DIS\` | 1 | 3, 5 |
| `EN.DVMA` | 1 | 4 |
| `EN.S4\` | 1 | 1 |
| `INIT\` | 1 | 1, 4, 7 |
| `P.A1` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.A10` | 2 | 1, 4, 5, 7 |
| `P.A2` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.A3` | 1 | 1, 3, 4, 5, 7 |
| `P.A4` | 1 | 1, 4, 5, 7 |
| `P.A5` | 1 | 1, 4, 5, 7 |
| `P.A6` | 1 | 1, 4, 5, 7 |
| `P.A7` | 1 | 1, 4, 7 |
| `P.A8` | 1 | 1, 4, 5, 7 |
| `P.A9` | 1 | 1, 4, 5, 7 |
| `P.AS\` | 1 | 1, 3, 5 |
| `P.BACK\` | 2 | 1, 3 |
| `P.BG\` | 1 | 1 |
| `P.BR\` | 1 | 1 |
| `P.FC1` | 1 | 1, 3 |
| `P.HALT\` | 1 | 1, 8 |
| `P.LDS\` | 1 | 1, 5, 7 |
| `P.R/W\` | 1 | 1, 3, 6 |
| `P.UDS\` | 1 | 1, 5 |
| `P1.A18\` | 1 | 7, 8 |
| `P1.A19\` | 1 | 7, 8 |
| `P1.A1\` | 1 | 7, 8 |
| `P1.BHEN\` | 1 | 7, 8 |
| `P1.MRDC\` | 2 | 7, 8 |
| `P1.MWTC\` | 1 | 7, 8 |
| `P1.XACK\` | 1 | 8 |
| `P1TOP` | 1 | 7 |
| `POR\` | 1 | 1, 4, 8 |
| `PROTERR\` | 1 | 1, 3, 4 |
| `Q.AS\` | 1 | 1, 7 |
| `REN\` | 3 | 8 |
| `RREQ\` | 2 | 7 |
| `SACK\` | 2 | *(Page 2 only)* |
| `SAS\` | 3 | *(Page 2 only)* |
| `SDS\` | 3 | 6 |
| `SYSB` | 2 | 5, 7 |
| `TIMEOUT\` | 5 | 1, 4 |
| `VALID` | 1 | 3 |
| `XBERR\` | 1 | 1 |
| `XEN\` | 2 | 7 |
| `XHALT\` | 1 | *(Page 2 only)* |
| `XREQ\` | 3 | *(Page 2 only)* |

### Page 3: MMU Context Register, Segment Map, Page Map, Protection Decoder, Statistics Bit Logic

**104 unique signals (233 instances):**

| Signal | Instances on Page | Also Appears On Pages |
|:-------|:-----------------:|:----------------------|
| `ACC` | 4 | *(Page 3 only)* |
| `BOOTEN\` | 1 | 4 |
| `C.S5` | 1 | 1, 2, 4 |
| `C.S6\` | 1 | 2, 7 |
| `CXS0` | 2 | *(Page 3 only)* |
| `CXS1` | 2 | *(Page 3 only)* |
| `CXS2` | 2 | *(Page 3 only)* |
| `CXS3` | 2 | *(Page 3 only)* |
| `CXU0` | 1 | *(Page 3 only)* |
| `CXU1` | 1 | *(Page 3 only)* |
| `CXU2` | 1 | *(Page 3 only)* |
| `CXU3` | 1 | *(Page 3 only)* |
| `DIS\` | 1 | 2, 5 |
| `DS\` | 1 | 1, 4, 5, 6 |
| `IA16` | 3 | *(Page 3 only)* |
| `IA17` | 3 | *(Page 3 only)* |
| `IA18` | 3 | *(Page 3 only)* |
| `IA19` | 3 | *(Page 3 only)* |
| `IA20` | 3 | *(Page 3 only)* |
| `IA21` | 3 | *(Page 3 only)* |
| `IA22` | 3 | *(Page 3 only)* |
| `IA23` | 3 | *(Page 3 only)* |
| `MA11` | 2 | 4, 5, 7 |
| `MA12` | 2 | 4, 5, 7 |
| `MA13` | 2 | 4, 5, 7 |
| `MA14` | 2 | 4, 5, 7 |
| `MA15` | 2 | 5, 7 |
| `MA16` | 2 | 5, 7 |
| `MA17` | 2 | 5, 7 |
| `MA18` | 2 | 5, 7 |
| `MA19` | 2 | 5, 7 |
| `MA20` | 2 | 5 |
| `MA21` | 2 | 5 |
| `MA22` | 2 | 5 |
| `MOD` | 4 | *(Page 3 only)* |
| `P.A1` | 3 | 1, 2, 4, 5, 6, 7 |
| `P.A11` | 1 | 1, 4, 7 |
| `P.A12` | 2 | 1, 4, 7 |
| `P.A13` | 1 | 1, 4, 7 |
| `P.A14` | 1 | 1, 4, 7 |
| `P.A15` | 1 | 1, 4, 7 |
| `P.A16` | 1 | 1, 7 |
| `P.A18` | 1 | 1, 7 |
| `P.A19` | 1 | 1, 7 |
| `P.A2` | 3 | 1, 2, 4, 5, 6, 7 |
| `P.A20` | 1 | 1, 7 |
| `P.A21` | 1 | 1, 7 |
| `P.A22` | 1 | 1, 7 |
| `P.A23` | 1 | 1, 7 |
| `P.A3` | 3 | 1, 2, 4, 5, 7 |
| `P.AS\` | 1 | 1, 2, 5 |
| `P.BACK\` | 1 | 1, 2 |
| `P.D0` | 4 | 1, 4, 5, 6, 7, 8 |
| `P.D1` | 7 | 1, 4, 5, 6, 7, 8 |
| `P.D10` | 4 | 1, 4, 5, 6, 7, 8 |
| `P.D11` | 4 | 1, 4, 5, 6, 7, 8 |
| `P.D12` | 2 | 1, 4, 5, 6, 7, 8 |
| `P.D13` | 2 | 1, 4, 5, 6, 7, 8 |
| `P.D14` | 2 | 1, 4, 5, 6, 7, 8 |
| `P.D15` | 2 | 1, 4, 5, 6, 7, 8 |
| `P.D2` | 6 | 1, 4, 5, 6, 7, 8 |
| `P.D3` | 5 | 1, 4, 5, 6, 7, 8 |
| `P.D4` | 3 | 1, 4, 5, 6, 7, 8 |
| `P.D5` | 3 | 1, 4, 5, 6, 7, 8 |
| `P.D6` | 3 | 4, 5, 6, 7, 8 |
| `P.D7` | 2 | 1, 4, 5, 6, 8 |
| `P.D8` | 4 | 1, 4, 5, 6, 7, 8 |
| `P.D9` | 3 | 1, 4, 5, 6, 7, 8 |
| `P.FC0` | 2 | 1 |
| `P.FC1` | 3 | 1, 2 |
| `P.FC2` | 3 | 1, 5, 6, 7 |
| `P.MMU\` | 4 | *(Page 3 only)* |
| `P.R/W\` | 1 | 1, 2, 6 |
| `P.SPROG\` | 1 | 4 |
| `PROT0` | 3 | *(Page 3 only)* |
| `PROT1` | 3 | *(Page 3 only)* |
| `PROT2` | 3 | *(Page 3 only)* |
| `PROT3` | 3 | *(Page 3 only)* |
| `PROT4` | 3 | *(Page 3 only)* |
| `PROT5` | 2 | *(Page 3 only)* |
| `PROTERR\` | 2 | 1, 2, 4 |
| `RD.CXL\` | 2 | *(Page 3 only)* |
| `RD.CXU\` | 2 | *(Page 3 only)* |
| `RD.ENABLE\` | 1 | 4 |
| `RD.ERROR\` | 1 | 4 |
| `RD.IDPROM\` | 1 | 4 |
| `RD.PMAP0L\` | 2 | *(Page 3 only)* |
| `RD.PMAP0U\` | 2 | *(Page 3 only)* |
| `RD.PMAP1L\` | 2 | *(Page 3 only)* |
| `RD.PMAP1U\` | 2 | *(Page 3 only)* |
| `RD.SMAP\` | 2 | *(Page 3 only)* |
| `TYPE0` | 1 | 1 |
| `TYPE1` | 4 | 1, 4, 7 |
| `VALID` | 2 | 2 |
| `WR.CXL\` | 2 | *(Page 3 only)* |
| `WR.CXU\` | 2 | *(Page 3 only)* |
| `WR.DIAG\` | 1 | 8 |
| `WR.ENABLE\` | 1 | 4 |
| `WR.PMAP0L\` | 3 | *(Page 3 only)* |
| `WR.PMAP0U\` | 3 | *(Page 3 only)* |
| `WR.PMAP0X\` | 2 | *(Page 3 only)* |
| `WR.PMAP1L\` | 3 | *(Page 3 only)* |
| `WR.PMAP1U\` | 3 | *(Page 3 only)* |
| `WR.SMAP\` | 3 | *(Page 3 only)* |

### Page 4: Strobe Decoders, Boot PROMs, Real-Time Clock (RTC), ID PROM, Bus Error Register, System Enable Register

**81 unique signals (139 instances):**

| Signal | Instances on Page | Also Appears On Pages |
|:-------|:-----------------:|:----------------------|
| `AEN\` | 1 | 2, 7 |
| `BOOTEN\` | 1 | 3 |
| `BOOT\` | 4 | *(Page 4 only)* |
| `C.S4\` | 1 | 2, 5 |
| `C.S5` | 1 | 1, 2, 3 |
| `DS\` | 1 | 1, 3, 5, 6 |
| `EN.DVMA` | 1 | 2 |
| `EN.INT` | 1 | 1 |
| `EN.INT1` | 1 | 1 |
| `EN.INT2` | 1 | 1 |
| `EN.INT3` | 1 | 1 |
| `EN.PARERR\` | 1 | 5 |
| `EN.PARGEN` | 1 | 5 |
| `IN2` | 1 | 8 |
| `INIT\` | 1 | 1, 2, 7 |
| `MA11` | 2 | 3, 5, 7 |
| `MA12` | 2 | 3, 5, 7 |
| `MA13` | 2 | 3, 5, 7 |
| `MA14` | 2 | 3, 5, 7 |
| `P.A1` | 2 | 1, 2, 3, 5, 6, 7 |
| `P.A10` | 1 | 1, 2, 5, 7 |
| `P.A11` | 2 | 1, 3, 7 |
| `P.A12` | 2 | 1, 3, 7 |
| `P.A13` | 2 | 1, 3, 7 |
| `P.A14` | 2 | 1, 3, 7 |
| `P.A15` | 4 | 1, 3, 7 |
| `P.A2` | 2 | 1, 2, 3, 5, 6, 7 |
| `P.A3` | 2 | 1, 2, 3, 5, 7 |
| `P.A4` | 2 | 1, 2, 5, 7 |
| `P.A5` | 2 | 1, 2, 5, 7 |
| `P.A6` | 1 | 1, 2, 5, 7 |
| `P.A7` | 1 | 1, 2, 7 |
| `P.A8` | 1 | 1, 2, 5, 7 |
| `P.A9` | 1 | 1, 2, 5, 7 |
| `P.D0` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D1` | 2 | 1, 3, 5, 6, 7, 8 |
| `P.D10` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D11` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D12` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D13` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D14` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D15` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D2` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D3` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D4` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D5` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D6` | 3 | 3, 5, 6, 7, 8 |
| `P.D7` | 3 | 1, 3, 5, 6, 8 |
| `P.D8` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.D9` | 3 | 1, 3, 5, 6, 7, 8 |
| `P.SPROG\` | 1 | 3 |
| `P.VPA\` | 1 | 1 |
| `PARERRL\` | 1 | 1, 5 |
| `PARERRU\` | 2 | 1, 5 |
| `POR\` | 1 | 1, 2, 8 |
| `PROTERR\` | 1 | 1, 2, 3 |
| `RD.DCP\` | 1 | 6 |
| `RD.ENABLE\` | 1 | 3 |
| `RD.ERROR\` | 1 | 3 |
| `RD.FPP\` | 1 | 6 |
| `RD.IDPROM\` | 1 | 3 |
| `RD.IO\` | 2 | *(Page 4 only)* |
| `RD.PORT\` | 1 | 8 |
| `RD.PROM\` | 2 | *(Page 4 only)* |
| `RD.RAM\` | 1 | 5 |
| `RD.ROP\` | 1 | 5 |
| `RD.RTC\` | 3 | *(Page 4 only)* |
| `RD.SCC\` | 1 | 6 |
| `RD.TIMER\` | 1 | 6 |
| `SBI\` | 1 | *(Page 4 only)* |
| `TIMEOUT\` | 1 | 1, 2 |
| `TYPE1` | 1 | 1, 3, 7 |
| `WR.DCP\` | 1 | 6 |
| `WR.ENABLE\` | 1 | 3 |
| `WR.FPP\` | 1 | 6 |
| `WR.IO\` | 2 | *(Page 4 only)* |
| `WR.RAM\` | 1 | 5 |
| `WR.ROP\` | 1 | 5 |
| `WR.RTC\` | 3 | *(Page 4 only)* |
| `WR.SCC\` | 1 | 6 |
| `WR.TIMER\` | 1 | 6 |

### Page 5: Rasterop Processor (ROP), Parity Check/Generation Logic, P2-Bus Interface

**124 unique signals (187 instances):**

| Signal | Instances on Page | Also Appears On Pages |
|:-------|:-----------------:|:----------------------|
| `AS\` | 1 | 1, 6 |
| `C.S3` | 1 | 2, 7 |
| `C.S3\` | 1 | 2 |
| `C.S4\` | 1 | 2, 4 |
| `C.S7` | 1 | 2, 6 |
| `DIS.D\` | 1 | *(Page 5 only)* |
| `DIS\` | 3 | 2, 3 |
| `DS\` | 1 | 1, 3, 4, 6 |
| `EN.PARERR\` | 1 | 4 |
| `EN.PARGEN` | 2 | 4 |
| `EN.PARGEN\` | 1 | 1 |
| `LD.DST\` | 5 | *(Page 5 only)* |
| `LD.SRC\` | 1 | *(Page 5 only)* |
| `MA11` | 1 | 3, 4, 7 |
| `MA12` | 1 | 3, 4, 7 |
| `MA13` | 1 | 3, 4, 7 |
| `MA14` | 1 | 3, 4, 7 |
| `MA15` | 1 | 3, 7 |
| `MA16` | 1 | 3, 7 |
| `MA17` | 1 | 3, 7 |
| `MA18` | 1 | 3, 7 |
| `MA19` | 1 | 3, 7 |
| `MA20` | 1 | 3 |
| `MA21` | 1 | 3 |
| `MA22` | 1 | 3 |
| `OE.ROP\` | 2 | 1 |
| `P.A1` | 3 | 1, 2, 3, 4, 6, 7 |
| `P.A10` | 1 | 1, 2, 4, 7 |
| `P.A2` | 4 | 1, 2, 3, 4, 6, 7 |
| `P.A3` | 3 | 1, 2, 3, 4, 7 |
| `P.A4` | 3 | 1, 2, 4, 7 |
| `P.A5` | 1 | 1, 2, 4, 7 |
| `P.A6` | 1 | 1, 2, 4, 7 |
| `P.A8` | 1 | 1, 2, 4, 7 |
| `P.A9` | 1 | 1, 2, 4, 7 |
| `P.AS\` | 1 | 1, 2, 3 |
| `P.D0` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D1` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D10` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D11` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D12` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D13` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D14` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D15` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D2` | 3 | 1, 3, 4, 6, 7, 8 |
| `P.D3` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D4` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D5` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D6` | 2 | 3, 4, 6, 7, 8 |
| `P.D7` | 1 | 1, 3, 4, 6, 8 |
| `P.D8` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.D9` | 2 | 1, 3, 4, 6, 7, 8 |
| `P.FC2` | 1 | 1, 3, 6, 7 |
| `P.LDS\` | 1 | 1, 2, 7 |
| `P.RESET\` | 1 | 1, 8 |
| `P.UDS\` | 2 | 1, 2 |
| `P2.A01` | 2 | 8 |
| `P2.A02` | 2 | 8 |
| `P2.A03` | 3 | 8 |
| `P2.A04` | 2 | 8 |
| `P2.A05` | 2 | 8 |
| `P2.A06` | 2 | 8 |
| `P2.A07` | 2 | 8 |
| `P2.A08` | 2 | 8 |
| `P2.A09` | 1 | 8 |
| `P2.A18` | 1 | 8 |
| `P2.A19` | 1 | 8 |
| `P2.A20` | 1 | 8 |
| `P2.A21` | 1 | 8 |
| `P2.A22` | 1 | 8 |
| `P2.CAS\` | 1 | 8 |
| `P2.DI0` | 1 | 8 |
| `P2.DI1` | 1 | 8 |
| `P2.DI10` | 2 | 8 |
| `P2.DI11` | 1 | 8 |
| `P2.DI12` | 1 | 8 |
| `P2.DI13` | 1 | 8 |
| `P2.DI14` | 1 | 8 |
| `P2.DI15` | 1 | 8 |
| `P2.DI2` | 1 | 8 |
| `P2.DI3` | 1 | 8 |
| `P2.DI4` | 1 | 8 |
| `P2.DI5` | 1 | 8 |
| `P2.DI6` | 1 | 8 |
| `P2.DI7` | 1 | 8 |
| `P2.DI8` | 1 | 8 |
| `P2.DI9` | 1 | 8 |
| `P2.DIL` | 1 | 8 |
| `P2.DIU` | 1 | 8 |
| `P2.DO0` | 2 | 8 |
| `P2.DO1` | 1 | 8 |
| `P2.DO10` | 2 | 8 |
| `P2.DO11` | 1 | 8 |
| `P2.DO12` | 1 | 8 |
| `P2.DO13` | 1 | 8 |
| `P2.DO14` | 1 | 8 |
| `P2.DO15` | 1 | 8 |
| `P2.DO2` | 1 | 8 |
| `P2.DO3` | 1 | 8 |
| `P2.DO4` | 1 | 8 |
| `P2.DO5` | 1 | 8 |
| `P2.DO6` | 1 | 8 |
| `P2.DO7` | 1 | 8 |
| `P2.DO8` | 1 | 8 |
| `P2.DO9` | 1 | 8 |
| `P2.DOL` | 1 | 8 |
| `P2.DOU` | 1 | 8 |
| `P2.R/W\` | 1 | 8 |
| `P2.RAS\` | 1 | 8 |
| `P2.WAIT\` | 1 | 1, 8 |
| `P2.WEL\` | 1 | 8 |
| `P2.WEU\` | 1 | 8 |
| `PARERRL\` | 1 | 1, 4 |
| `PARERRU\` | 1 | 1, 4 |
| `RD.RAM\` | 5 | 4 |
| `RD.ROP\` | 2 | 4 |
| `ROPCYC\` | 2 | 1 |
| `ROPST0` | 3 | *(Page 5 only)* |
| `ROPST1` | 3 | *(Page 5 only)* |
| `ROPST2` | 3 | *(Page 5 only)* |
| `SYSB` | 1 | 2, 7 |
| `WR.M\` | 5 | *(Page 5 only)* |
| `WR.RAM\` | 1 | 4 |
| `WR.ROP\` | 2 | 4 |

### Page 6: Floating-Point Processor (80287 FPP), Data Cipher Processor (Am9518 DCP), System Timer (Am9513), Dual Serial Controller (Z8530 SCC), RS423 Drivers

**76 unique signals (139 instances):**

| Signal | Instances on Page | Also Appears On Pages |
|:-------|:-----------------:|:----------------------|
| `AS\` | 3 | 1, 5 |
| `AUX0` | 1 | *(Page 6 only)* |
| `AUX1` | 1 | *(Page 6 only)* |
| `AUX2` | 1 | *(Page 6 only)* |
| `AUX3` | 1 | *(Page 6 only)* |
| `AUX4` | 1 | *(Page 6 only)* |
| `AUX5` | 1 | *(Page 6 only)* |
| `AUX7` | 1 | *(Page 6 only)* |
| `C.S7` | 1 | 2, 5 |
| `CLK` | 2 | 1, 7 |
| `CTSA\` | 2 | *(Page 6 only)* |
| `CTSB\` | 2 | 8 |
| `DCDA\` | 2 | *(Page 6 only)* |
| `DCDB\` | 3 | 8 |
| `DSRA\` | 2 | *(Page 6 only)* |
| `DSRB\` | 3 | 8 |
| `DS\` | 3 | 1, 3, 4, 5 |
| `DTRA\` | 2 | 8 |
| `DTRB\` | 4 | 8 |
| `ENVEE` | 2 | *(Page 6 only)* |
| `FOUT` | 2 | *(Page 6 only)* |
| `FPPERR\` | 1 | 1 |
| `INT.SCC\` | 1 | 1 |
| `INT5\` | 4 | 1, 8 |
| `INT7\` | 1 | *(Page 6 only)* |
| `IOACK\` | 1 | 1 |
| `P.A1` | 4 | 1, 2, 3, 4, 5, 7 |
| `P.A2` | 3 | 1, 2, 3, 4, 5, 7 |
| `P.D0` | 2 | 1, 3, 4, 5, 7, 8 |
| `P.D1` | 1 | 1, 3, 4, 5, 7, 8 |
| `P.D10` | 4 | 1, 3, 4, 5, 7, 8 |
| `P.D11` | 4 | 1, 3, 4, 5, 7, 8 |
| `P.D12` | 4 | 1, 3, 4, 5, 7, 8 |
| `P.D13` | 4 | 1, 3, 4, 5, 7, 8 |
| `P.D14` | 4 | 1, 3, 4, 5, 7, 8 |
| `P.D15` | 4 | 1, 3, 4, 5, 7, 8 |
| `P.D2` | 2 | 1, 3, 4, 5, 7, 8 |
| `P.D3` | 1 | 1, 3, 4, 5, 7, 8 |
| `P.D4` | 1 | 1, 3, 4, 5, 7, 8 |
| `P.D5` | 1 | 1, 3, 4, 5, 7, 8 |
| `P.D6` | 1 | 3, 4, 5, 7, 8 |
| `P.D7` | 1 | 1, 3, 4, 5, 8 |
| `P.D8` | 4 | 1, 3, 4, 5, 7, 8 |
| `P.D9` | 4 | 1, 3, 4, 5, 7, 8 |
| `P.FC2` | 1 | 1, 3, 5, 7 |
| `P.R/W\` | 1 | 1, 2, 3 |
| `PCLK` | 1 | *(Page 6 only)* |
| `RD.DCP\` | 1 | 4 |
| `RD.FPP\` | 2 | 4 |
| `RD.SCC\` | 1 | 4 |
| `RD.TIMER\` | 1 | 4 |
| `RTSA\` | 3 | *(Page 6 only)* |
| `RTSB\` | 2 | 8 |
| `RXCA\` | 2 | *(Page 6 only)* |
| `RXCB\` | 2 | *(Page 6 only)* |
| `RXDA` | 2 | *(Page 6 only)* |
| `RXDB` | 2 | *(Page 6 only)* |
| `SDS\` | 1 | 2 |
| `SP0` | 1 | *(Page 6 only)* |
| `SP1` | 1 | *(Page 6 only)* |
| `SP2` | 1 | *(Page 6 only)* |
| `SP3` | 1 | *(Page 6 only)* |
| `SP4` | 1 | *(Page 6 only)* |
| `SP5` | 1 | *(Page 6 only)* |
| `SP6` | 1 | *(Page 6 only)* |
| `SP7` | 1 | *(Page 6 only)* |
| `TXCA\` | 1 | *(Page 6 only)* |
| `TXCB\` | 2 | *(Page 6 only)* |
| `TXDA` | 1 | *(Page 6 only)* |
| `TXDB` | 1 | *(Page 6 only)* |
| `VEEA` | 1 | 8 |
| `VEEB` | 1 | 8 |
| `WR.DCP\` | 1 | 4 |
| `WR.FPP\` | 2 | 4 |
| `WR.SCC\` | 1 | 4 |
| `WR.TIMER\` | 1 | 4 |

### Page 7: Multibus (P1) Address Out, Address In, Data Buffers, Bus Arbiter (8289)

**118 unique signals (173 instances):**

| Signal | Instances on Page | Also Appears On Pages |
|:-------|:-----------------:|:----------------------|
| `ABCS` | 3 | *(Page 7 only)* |
| `AEN\` | 3 | 2, 4 |
| `BEN\` | 1 | 2 |
| `BPRN\` | 1 | *(Page 7 only)* |
| `BREQ\` | 1 | *(Page 7 only)* |
| `C.S3` | 1 | 2, 5 |
| `C.S4` | 1 | 1 |
| `C.S6\` | 1 | 2, 3 |
| `CE.BYTE\` | 1 | 2 |
| `CE.WORD\` | 1 | 2 |
| `CLK` | 1 | 1, 6 |
| `INIT\` | 1 | 1, 2, 4 |
| `IOB\` | 2 | *(Page 7 only)* |
| `MA11` | 1 | 3, 4, 5 |
| `MA12` | 1 | 3, 4, 5 |
| `MA13` | 1 | 3, 4, 5 |
| `MA14` | 1 | 3, 4, 5 |
| `MA15` | 1 | 3, 5 |
| `MA16` | 1 | 3, 5 |
| `MA17` | 1 | 3, 5 |
| `MA18` | 1 | 3, 5 |
| `MA19` | 1 | 3, 5 |
| `P.A1` | 2 | 1, 2, 3, 4, 5, 6 |
| `P.A10` | 2 | 1, 2, 4, 5 |
| `P.A11` | 1 | 1, 3, 4 |
| `P.A12` | 1 | 1, 3, 4 |
| `P.A13` | 1 | 1, 3, 4 |
| `P.A14` | 1 | 1, 3, 4 |
| `P.A15` | 1 | 1, 3, 4 |
| `P.A16` | 1 | 1, 3 |
| `P.A17` | 1 | 1 |
| `P.A18` | 1 | 1, 3 |
| `P.A19` | 1 | 1, 3 |
| `P.A2` | 2 | 1, 2, 3, 4, 5, 6 |
| `P.A20` | 1 | 1, 3 |
| `P.A21` | 1 | 1, 3 |
| `P.A22` | 1 | 1, 3 |
| `P.A23` | 1 | 1, 3 |
| `P.A3` | 2 | 1, 2, 3, 4, 5 |
| `P.A4` | 2 | 1, 2, 4, 5 |
| `P.A5` | 2 | 1, 2, 4, 5 |
| `P.A6` | 1 | 1, 2, 4, 5 |
| `P.A7` | 2 | 1, 2, 4 |
| `P.A8` | 2 | 1, 2, 4, 5 |
| `P.A9` | 2 | 1, 2, 4, 5 |
| `P.D0` | 1 | 1, 3, 4, 5, 6, 8 |
| `P.D1` | 1 | 1, 3, 4, 5, 6, 8 |
| `P.D10` | 2 | 1, 3, 4, 5, 6, 8 |
| `P.D11` | 2 | 1, 3, 4, 5, 6, 8 |
| `P.D12` | 2 | 1, 3, 4, 5, 6, 8 |
| `P.D13` | 2 | 1, 3, 4, 5, 6, 8 |
| `P.D14` | 2 | 1, 3, 4, 5, 6, 8 |
| `P.D15` | 2 | 1, 3, 4, 5, 6, 8 |
| `P.D2` | 2 | 1, 3, 4, 5, 6, 8 |
| `P.D3` | 1 | 1, 3, 4, 5, 6, 8 |
| `P.D4` | 1 | 1, 3, 4, 5, 6, 8 |
| `P.D5` | 1 | 1, 3, 4, 5, 6, 8 |
| `P.D6` | 1 | 3, 4, 5, 6, 8 |
| `P.D8` | 2 | 1, 3, 4, 5, 6, 8 |
| `P.D9` | 2 | 1, 3, 4, 5, 6, 8 |
| `P.FC2` | 1 | 1, 3, 5, 6 |
| `P.LDS\` | 1 | 1, 2, 5 |
| `P1.A0\` | 1 | 8 |
| `P1.A10\` | 2 | 8 |
| `P1.A11\` | 2 | 8 |
| `P1.A12\` | 2 | 8 |
| `P1.A13\` | 2 | 8 |
| `P1.A14\` | 2 | 8 |
| `P1.A15\` | 3 | 8 |
| `P1.A16\` | 2 | 8 |
| `P1.A17\` | 2 | 8 |
| `P1.A18\` | 2 | 2, 8 |
| `P1.A19\` | 2 | 2, 8 |
| `P1.A1\` | 3 | 2, 8 |
| `P1.A2\` | 2 | 8 |
| `P1.A3\` | 2 | 8 |
| `P1.A4\` | 2 | 8 |
| `P1.A5\` | 2 | 8 |
| `P1.A6\` | 2 | 8 |
| `P1.A7\` | 2 | 8 |
| `P1.A8\` | 2 | 8 |
| `P1.A9\` | 2 | 8 |
| `P1.BCLK\` | 2 | 8 |
| `P1.BHEN\` | 1 | 2, 8 |
| `P1.BPRN\` | 1 | 8 |
| `P1.BPRO\` | 1 | 8 |
| `P1.BREQ\` | 1 | 8 |
| `P1.BUSY\` | 1 | 8 |
| `P1.CBRQ\` | 1 | 8 |
| `P1.CCLK\` | 1 | 8 |
| `P1.D0\` | 1 | 8 |
| `P1.D10\` | 1 | 8 |
| `P1.D11\` | 2 | 8 |
| `P1.D12\` | 1 | 8 |
| `P1.D13\` | 1 | 8 |
| `P1.D14\` | 1 | 8 |
| `P1.D15\` | 1 | 8 |
| `P1.D1\` | 2 | 8 |
| `P1.D2\` | 2 | 8 |
| `P1.D3\` | 2 | 8 |
| `P1.D4\` | 2 | 8 |
| `P1.D5\` | 2 | 8 |
| `P1.D6\` | 2 | 8 |
| `P1.D7\` | 2 | 8 |
| `P1.D8\` | 1 | 8 |
| `P1.D9\` | 1 | 8 |
| `P1.INIT\` | 2 | 1, 8 |
| `P1.IORC\` | 1 | 8 |
| `P1.IOWC\` | 1 | 8 |
| `P1.MRDC\` | 1 | 2, 8 |
| `P1.MWTC\` | 1 | 2, 8 |
| `P1TOP` | 1 | 2 |
| `Q.AS\` | 1 | 1, 2 |
| `RREQ\` | 1 | 2 |
| `SYSB` | 1 | 2, 5 |
| `TYPE1` | 1 | 1, 3, 4 |
| `XACK\` | 2 | 1 |
| `XEN\` | 1 | 2 |

### Page 8: Diagnostic Register, Diagnostic Input Port, Multibus P1 Connector (P86), Sun P2 Connector (P60), Serial DB Connectors

**177 unique signals (231 instances):**

| Signal | Instances on Page | Also Appears On Pages |
|:-------|:-----------------:|:----------------------|
| `CTSB\` | 1 | 6 |
| `DCDB\` | 1 | 6 |
| `DSRB\` | 1 | 6 |
| `DTRA\` | 1 | 6 |
| `DTRB\` | 1 | 6 |
| `IN0` | 1 | *(Page 8 only)* |
| `IN1` | 3 | *(Page 8 only)* |
| `IN10` | 3 | *(Page 8 only)* |
| `IN11` | 3 | *(Page 8 only)* |
| `IN12` | 3 | *(Page 8 only)* |
| `IN13` | 3 | *(Page 8 only)* |
| `IN14` | 3 | *(Page 8 only)* |
| `IN15` | 3 | *(Page 8 only)* |
| `IN2` | 3 | 4 |
| `IN3` | 3 | *(Page 8 only)* |
| `IN4` | 3 | *(Page 8 only)* |
| `IN5` | 2 | *(Page 8 only)* |
| `IN7` | 3 | *(Page 8 only)* |
| `IN8` | 3 | *(Page 8 only)* |
| `IN9` | 3 | *(Page 8 only)* |
| `INT1\` | 1 | 1 |
| `INT2\` | 3 | 1 |
| `INT3\` | 1 | 1 |
| `INT4\` | 1 | 1 |
| `INT5\` | 1 | 1, 6 |
| `INT6\` | 1 | 1 |
| `LED0` | 2 | *(Page 8 only)* |
| `LED1` | 2 | *(Page 8 only)* |
| `LED2` | 2 | *(Page 8 only)* |
| `LED3` | 2 | *(Page 8 only)* |
| `LED4` | 4 | *(Page 8 only)* |
| `LED5` | 1 | *(Page 8 only)* |
| `LED6` | 2 | *(Page 8 only)* |
| `LED7` | 1 | *(Page 8 only)* |
| `P.D0` | 2 | 1, 3, 4, 5, 6, 7 |
| `P.D1` | 2 | 1, 3, 4, 5, 6, 7 |
| `P.D10` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.D11` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.D12` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.D13` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.D14` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.D15` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.D2` | 2 | 1, 3, 4, 5, 6, 7 |
| `P.D3` | 2 | 1, 3, 4, 5, 6, 7 |
| `P.D4` | 2 | 1, 3, 4, 5, 6, 7 |
| `P.D5` | 2 | 1, 3, 4, 5, 6, 7 |
| `P.D6` | 2 | 3, 4, 5, 6, 7 |
| `P.D7` | 2 | 1, 3, 4, 5, 6 |
| `P.D8` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.D9` | 1 | 1, 3, 4, 5, 6, 7 |
| `P.HALT\` | 1 | 1, 2 |
| `P.RESET\` | 2 | 1, 5 |
| `P1.A0\` | 1 | 7 |
| `P1.A10\` | 1 | 7 |
| `P1.A11\` | 1 | 7 |
| `P1.A12\` | 1 | 7 |
| `P1.A13\` | 1 | 7 |
| `P1.A14\` | 1 | 7 |
| `P1.A15\` | 1 | 7 |
| `P1.A16\` | 1 | 7 |
| `P1.A17\` | 1 | 7 |
| `P1.A18\` | 1 | 2, 7 |
| `P1.A19\` | 1 | 2, 7 |
| `P1.A1\` | 1 | 2, 7 |
| `P1.A2\` | 1 | 7 |
| `P1.A3\` | 1 | 7 |
| `P1.A4\` | 1 | 7 |
| `P1.A5\` | 1 | 7 |
| `P1.A6\` | 1 | 7 |
| `P1.A7\` | 1 | 7 |
| `P1.A8\` | 1 | 7 |
| `P1.A9\` | 1 | 7 |
| `P1.AACK\` | 1 | *(Page 8 only)* |
| `P1.BCLK\` | 1 | 7 |
| `P1.BHEN\` | 1 | 2, 7 |
| `P1.BPRN\` | 1 | 7 |
| `P1.BPRO\` | 1 | 7 |
| `P1.BREQ\` | 1 | 7 |
| `P1.BUSY\` | 1 | 7 |
| `P1.CBRQ\` | 1 | 7 |
| `P1.CCLK\` | 1 | 7 |
| `P1.D0\` | 1 | 7 |
| `P1.D10\` | 1 | 7 |
| `P1.D11\` | 1 | 7 |
| `P1.D12\` | 1 | 7 |
| `P1.D13\` | 1 | 7 |
| `P1.D14\` | 1 | 7 |
| `P1.D15\` | 1 | 7 |
| `P1.D1\` | 1 | 7 |
| `P1.D2\` | 1 | 7 |
| `P1.D3\` | 1 | 7 |
| `P1.D4\` | 1 | 7 |
| `P1.D5\` | 1 | 7 |
| `P1.D6\` | 1 | 7 |
| `P1.D7\` | 1 | 7 |
| `P1.D8\` | 1 | 7 |
| `P1.D9\` | 1 | 7 |
| `P1.INH1\` | 1 | *(Page 8 only)* |
| `P1.INH2\` | 1 | *(Page 8 only)* |
| `P1.INIT\` | 1 | 1, 7 |
| `P1.INT0\` | 1 | *(Page 8 only)* |
| `P1.INT1\` | 2 | *(Page 8 only)* |
| `P1.INT2\` | 2 | *(Page 8 only)* |
| `P1.INT3\` | 2 | *(Page 8 only)* |
| `P1.INT4\` | 2 | *(Page 8 only)* |
| `P1.INT5\` | 2 | *(Page 8 only)* |
| `P1.INT6\` | 2 | *(Page 8 only)* |
| `P1.INT7\` | 2 | *(Page 8 only)* |
| `P1.INTA\` | 1 | *(Page 8 only)* |
| `P1.IORC\` | 1 | 7 |
| `P1.IOWC\` | 1 | 7 |
| `P1.MRDC\` | 1 | 2, 7 |
| `P1.MWTC\` | 1 | 2, 7 |
| `P1.XACK\` | 1 | 2 |
| `P2.A01` | 1 | 5 |
| `P2.A02` | 1 | 5 |
| `P2.A03` | 1 | 5 |
| `P2.A04` | 1 | 5 |
| `P2.A05` | 1 | 5 |
| `P2.A06` | 1 | 5 |
| `P2.A07` | 1 | 5 |
| `P2.A08` | 1 | 5 |
| `P2.A09` | 1 | 5 |
| `P2.A18` | 1 | 5 |
| `P2.A19` | 1 | 5 |
| `P2.A20` | 1 | 5 |
| `P2.A21` | 1 | 5 |
| `P2.A22` | 1 | 5 |
| `P2.CAS\` | 1 | 5 |
| `P2.DI0` | 1 | 5 |
| `P2.DI1` | 1 | 5 |
| `P2.DI10` | 1 | 5 |
| `P2.DI11` | 1 | 5 |
| `P2.DI12` | 1 | 5 |
| `P2.DI13` | 1 | 5 |
| `P2.DI14` | 1 | 5 |
| `P2.DI15` | 1 | 5 |
| `P2.DI2` | 1 | 5 |
| `P2.DI3` | 1 | 5 |
| `P2.DI4` | 1 | 5 |
| `P2.DI5` | 1 | 5 |
| `P2.DI6` | 1 | 5 |
| `P2.DI7` | 1 | 5 |
| `P2.DI8` | 1 | 5 |
| `P2.DI9` | 1 | 5 |
| `P2.DIL` | 1 | 5 |
| `P2.DIU` | 1 | 5 |
| `P2.DO0` | 1 | 5 |
| `P2.DO1` | 1 | 5 |
| `P2.DO10` | 1 | 5 |
| `P2.DO11` | 1 | 5 |
| `P2.DO12` | 1 | 5 |
| `P2.DO13` | 1 | 5 |
| `P2.DO14` | 1 | 5 |
| `P2.DO15` | 1 | 5 |
| `P2.DO2` | 1 | 5 |
| `P2.DO3` | 1 | 5 |
| `P2.DO4` | 1 | 5 |
| `P2.DO5` | 1 | 5 |
| `P2.DO6` | 1 | 5 |
| `P2.DO7` | 1 | 5 |
| `P2.DO8` | 1 | 5 |
| `P2.DO9` | 1 | 5 |
| `P2.DOL` | 1 | 5 |
| `P2.DOU` | 1 | 5 |
| `P2.R/W\` | 1 | 5 |
| `P2.RAS\` | 1 | 5 |
| `P2.WAIT\` | 1 | 1, 5 |
| `P2.WEL\` | 1 | 5 |
| `P2.WEU\` | 1 | 5 |
| `POR\` | 2 | 1, 2, 4 |
| `RD.PORT\` | 1 | 4 |
| `REN\` | 1 | 2 |
| `RTSB\` | 1 | 6 |
| `VEEA` | 1 | 6 |
| `VEEB` | 1 | 6 |
| `WR.DIAG\` | 1 | 3 |

### Page 9: Power Distribution & Bypass Capacitors

*(No signal lines — power distribution and bypass capacitors only)*


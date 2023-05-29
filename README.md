**Work-In-Progress** : [PCB Gerbers](https://github.com/mwrnd/AlveoU25_JTAG_Adapter/releases/download/v0.1-alpha/AlveoU25_JTAG_Adapter-Gerbers.zip) ready but not yet ordered.

# AlveoU25_JTAG_Adapter

Alveo U25 Debug Connector to Xilinx JTAG, UART, and I2C. The pinout is not available publicly so the signals had to be [traced out](https://github.com/mwrnd/notes/blob/main/Alveo_U25/debug_log.md#figuring-out-the-jtag-debug-connector).

![Tracing Alveo U25 JTAG Signals](img/U25_JTAG_Debug_Header_Signal_Tracing.jpg)




## Schematic

![Schematic](img/Alveo_U25_Debug_Adapter_PCB_Schematic.png)




## PCB Layout

![PCB Layout](img/Alveo_U25_Debug_Adapter_PCB_Layout.png)




## Bill Of Materials

| Designator(s)    | Part Number          | Footprint         | Availability                                                     |
| ---------------- | -------------------- | ----------------- | ---------------------------------------------------------------- |
| U1               | MEC8-113-02-L-D-RA1  | MEC8-113-02-L-D   | [1](https://www.trustedparts.com/en/search/MEC8-113-02-L-D-RA1)  |
| J1               | SBH21-NBPN-D07-ST-BK | SBH21-NBPN-D07-ST | [1](https://www.trustedparts.com/en/search/SBH21-NBPN-D07-ST-BK) |
| U5               | 74AVC4T774PW         | TSSOP-16          | [1](https://www.trustedparts.com/en/search/74AVC4T774PW)         |
| JP1, JP2, J5, J7 | PPTC061LFBN-RC       | 1x06_2.54mm       | [1](https://www.trustedparts.com/en/search/PPTC061LFBN-RC)       |
| J3, J4           | PPTC082LFBN-RC       | 2x04_2.54x2.54mm  | [1](https://www.trustedparts.com/en/search/PPTC082LFBN-RC)       |
| J6               | PREC002DAAN-RC       | 2x02_2.54mm       | [1](https://www.trustedparts.com/en/search/PREC002DAAN-RC)       |
| R14, R15         | RNCP0603FTD10K0      | 0603              | [1](https://www.trustedparts.com/en/search/RNCP0603FTD10K0)      |
| C4, C5           | CL10B104JB8NNNC      | 0603              | [1](https://www.trustedparts.com/en/search/CL10B104JB8NNNC)      |
| x                | Adafruit 4471        | None - Module     | [1](https://www.trustedparts.com/en/part/adafruit/4471)          |
| x, x             | STC02SYAN            | None - Jumper     | [1](https://www.trustedparts.com/en/search/STC02SYAN)            |




## Previous Version

[`v0.1-alpha`](https://github.com/mwrnd/AlveoU25_JTAG_Adapter/releases/tag/v0.1-alpha) was a basic breakout board for the Alveo U25 Debug Connector.

Only two components were required: [MEC8-113-02-L-D-RA1](https://www.trustedparts.com/en/search/MEC8-113-02-L-D-RA1) and [SBH21-NBPN-D07-ST-BK](https://www.trustedparts.com/en/search/SBH21-NBPN-D07-ST-BK).

![Alveo U25 to Xilinx JTAG Adapter](img/AlveoU25_JTAG_Adapter.png)


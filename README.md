# RP2350A Minimal Board KICad with USBC LCSC/JLCPCB parts

The primary goal of this project is to have a reference design for RP2350A, that uses USBC and has the LCSC/JLCPCB parts defined.

A secondary goal is to make the design physically small as possiable with one side SMD assembly.

**DO NOT USE** - This design has not been tested yet.

## Parts

- Microcontroller - [RP2350A](https://jlcpcb.com/partdetail/RaspberryPi-RP2350A/C42411118) (C42411118)
- Polarised inductor [Abracon AOTA-B201610S3R3-101-T](https://jlcpcb.com/partdetail/AbraconLlc-AOTA_B201610S3R3_101T/C42411119) (C42411119)
- Crystal oscillator [12 MHz Abracon ABM8-272-T3](https://jlcpcb.com/partdetail/AbraconLlc-ABM8_272T3/C20625731) (C20625731)
- 4Mb Flash - [Winbond Elec W25Q32JVUUIQ](https://jlcpcb.com/partdetail/WinbondElec-W25Q32JVUUIQ/C2999380) (C2999380)
- USB TYPE-C - [SHOU HAN USB TYPE-C 16PIN 2MD](https://jlcpcb.com/partdetail/ShouHan-TYPE_C_16PIN_2MD_073/C2765186) (C2765186) * Extended
- 3.3v Voltage Regulators - [AMS1117-3.3](https://jlcpcb.com/partdetail/Advanced_MonolithicSystems-AMS1117_33/C6186) (C6186)

## Design

The base design files came from [https://datasheets.raspberrypi.com/rp2350/Minimal-KiCAD.zip](https://datasheets.raspberrypi.com/rp2350/Minimal-KiCAD.zip)

I am trying to copy the power supply design from the [EasyEDA reference design with USBC](https://oshwlab.com/lckfb-team/coloreasypicox)

So that I can use the JLCPCB cupon here [RP2350 now available to buy: a high-performance, secure microcontroller for your next project](https://www.raspberrypi.com/news/rp2350-now-available-to-buy-a-high-performance-secure-microcontroller-for-your-next-project/)

## Helpful Links

- [KiCanvas](https://kicanvas.org/?github=https://github.com/funvill/RP2350A_Minimal_USBC/tree/main/RP-006440-DD-2-RP2350A%20Minimal%20Board%20Kicad%20archive) - In browser view of the KiCad files.
- [Hardware Design With RP2350](https://datasheets.raspberrypi.com/rp2350/hardware-design-with-rp2350.pdf)
- [EasyEDA2Kicad](https://github.com/uPesy/easyeda2kicad.py) - Converts JLCPCB parts to KiCad files.

# RP2350A Minimal Board KICad with USBC LCSC/JLCPCB parts

The primary goal of this project is to have a reference design for RP2350A, that uses USBC and has the LCSC/JLCPCB parts defined.

A secondary goal is to make the design physically small as possiable with one side SMD assembly.

**DO NOT USE** - This design has not been tested yet.

## Parts

- Polarised inductor [Abracon AOTA-B201610S3R3-101-T](https://jlcpcb.com/partdetail/AbraconLlc-AOTA_B201610S3R3_101T/C42411119) (C42411119)
- Crystal oscillator [12 MHz Abracon ABM8-272-T3](https://jlcpcb.com/partdetail/AbraconLlc-ABM8_272T3/C20625731) (C20625731)
- 4Mb Flash - [Winbond Elec W25Q32JVUUIQ](https://jlcpcb.com/partdetail/WinbondElec-W25Q32JVUUIQ/C2999380) (C2999380)

## Design

The base design files came from [https://datasheets.raspberrypi.com/rp2350/Minimal-KiCAD.zip](https://datasheets.raspberrypi.com/rp2350/Minimal-KiCAD.zip)

I am trying to copy the power supply design from the [EasyEDA reference design with USBC](https://oshwlab.com/lckfb-team/coloreasypicox)

So that I can use the JLCPCB cupon here [RP2350 now available to buy: a high-performance, secure microcontroller for your next project](https://www.raspberrypi.com/news/rp2350-now-available-to-buy-a-high-performance-secure-microcontroller-for-your-next-project/)

## Helpful Links

- [KiCanvas](https://kicanvas.org/?github=) - In browser view of the KiCad files.
- [Hardware Design With RP2350](https://datasheets.raspberrypi.com/rp2350/hardware-design-with-rp2350.pdf)

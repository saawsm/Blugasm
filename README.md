# SW-32, a collection of MK-312 style drivers
<img align="center" src="doc/SW-3211M.png">

## About
This project aims to bring the hardware of e-stim/EMS/TENS to an easy-to-use module. Think: Sparkfun, Adafruit, etc.

The device tries to mimic the output stage of the well-known Erostec ET312 or better, the DIY reverse engineered MK-312. 
Hopefully by recreating this output stage, the same e-stim experience can be achieved as those devices.

Its been designed with the ESP-32 microcontroller in mind (hence SW-32), but should work with others. 

## Projects
The project is split into multiple sub-projects all based around the easy-to-use module (SW-3211M)
- [SW-3211M](/hardware/SW-3211M) - The easy-to-use module board. This could be considered the core project.
- [SW-3221](/hardware/SW-3221) - A 2 channel e-stim board based around the module and the ESP-32.

Currently the only design available is the SW-3211M; a single channel module board. I plan on creating other boards in the future such as a dual/quad channel boards with an integrated ESP-32.

More detailed information about each sub-project can be found in the project specific READMEs.

## Status
Project status about hardware can be found in the project specific READMEs.

## Acknowledgments
The design of the module board (SW-3211M) was based on the design by [WendyTeslaburger/WT-312](https://github.com/WendyTeslaburger/WT-312).

## License
All hardware design, software, images and documentation are licensed under the Creative Commons license.

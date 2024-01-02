# NanoVNA-H Project

## Introduction
This repository contains the firmware for the NanoVNA-H device, which is an open-source handheld Vector Network Analyzer. The main functionality is coded in `main.c`, which interfaces with various hardware components to perform RF sweeps and analyze circuits.

## Software Setup

### Eclipse
- Download and install Eclipse CDT (C/C++ Development Tooling).
- Install the GNU MCU Eclipse plug-ins.
- Import the existing project into Eclipse.
- Configure the build settings according to the `Makefile`.

### Dependencies
Here is a list of other tools/packages that need to be installed before starting Eclipse.

Tip: If you already started Eclipse, close it, install these tools, and reopen Eclipse.
- node/npm/xpm - although not mandatory by Eclipse itself, it is highly recommended to use xpm (the xPack Project Manager, which is a Node.js portable CLI application) to install various build tools
- (the Hello World Arm/RISC-V QEMU xPack project template mandates it)
- Windows Build Tools - to build projects, on Windows it is necessary to install make, available from the xPack Windows Build Tools;
- Arm Embedded GCC toolchain - to build Arm projects, an Arm toolchain like the xPack GNU Arm Embedded GCC is required;
- RISC-V Embedded GCC toolchain - similarly, for RISC-V projects, a RISC-V toolchain like the xPack GNU RISC-V Embedded GCC is required;
- SEGGER J-Link - to debug projects, a JTAG probe is necessary together with the software to access it, for example the SEGGER J-Link software;
- OpenOCD - for some boards, xPack OpenOCD might also be useful;
- QEMU Arm - to run debug sessions without actual hardware, the xPack QEMU Arm emulator is necessary (the blinky tutorial mandates it).
- QEMU RISC-V - similarly, the xPack QEMU RISC-V emulator is useful to run RISC-V application (the Hello World RISC-V tutorial mandates it).

## Hardware Connections
Provide detailed instructions on how to connect the NanoVNA-H hardware, including any necessary cables or peripherals.

## Code Description

### main.c
The `main.c` file is responsible for:
- Initializing the system and hardware components.
- Managing the main operation loop for RF sweeps.
- Handling user input and providing a command-line interface for device control.
- Executing signal processing algorithms for RF data.

### board.c
The `board.c` file includes:
- Initial hardware setup and configuration.
- Pin definitions and initialization code required before the main application starts.

## Usage
Make sure to connect the NanoVNA-H using a USB-A port on the computer and then connect the Bluetooth HC-05 terminals 

## Contact
- Email me if you have any questions: lisa.miladi@gmail.com



## [](https://github.com/ttrftech/NanoVNA#control-from-pc)Control from PC

See [python directory](https://github.com/ttrftech/NanoVNA/blob/master/python/README.md).

## [](https://github.com/ttrftech/NanoVNA#note)Note


## [](https://github.com/ttrftech/NanoVNA#reference)Reference

*   [Schematics](https://github.com/ttrftech/NanoVNA/blob/master/doc/nanovna-sch.pdf)
*   [PCB Photo](https://github.com/ttrftech/NanoVNA/blob/master/doc/nanovna-pcb-photo.jpg)
*   [Block Diagram](https://github.com/ttrftech/NanoVNA/blob/master/doc/nanovna-blockdiagram.png)
*   Kit available from [https://ttrf.tk/kit/nanovna](https://ttrf.tk/kit/nanovna)

## [](https://github.com/ttrftech/NanoVNA#credit)Credit

*   [@edy555](https://github.com/edy555)

### [](https://github.com/ttrftech/NanoVNA#contributors)Contributors

*   [@hugen79](https://github.com/hugen79)
*   [@cho45](https://github.com/cho45)

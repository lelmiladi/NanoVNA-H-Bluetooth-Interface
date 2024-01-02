# NanoVNA-H-Bluetooth-Interface


## Introduction
This repository contains the firmware for the NanoVNA-H device, which is an open-source handheld Vector Network Analyzer. The main functionality is coded in `main.c`, which interfaces with various hardware components to perform RF sweeps and analyze circuits.

## Software Setup

### Eclipse
- Download and install Eclipse CDT (C/C++ Development Tooling).
- Install the GNU MCU Eclipse plug-ins.
- Import the existing project into Eclipse.
- Configure the build settings according to the `Makefile`.

### Dependencies
- List any libraries or tools that need to be installed.

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
- Make sure the Bluetooth terminals are connected correctly
- Connect the NanoVNA to your computer where you are running the software

## Contributing
Guidelines on how to contribute to the project, if open to contributions.

## Contact
- Email: Lisa.miladi@gmail.com
- Cell: 720-600-3350

# Own_RPI_Streamer_PCB

PCB files for RPI Streamer Board

# Description

This is a main board to hold a Raspberry Pi (4) and the Hifyberry Digi2 Pro expansion board. This puts the connections I need (for me) on one side to be able to build my own streamer.

- Part 1

The internal "power supply" (Pololu S13V30F5) delivers at 5V@3A, sensor and RGB are powered by part 2.

There is a temperature sensor (Sensirion SHT45) under the SoC and an additional unregulated fan connector (e.g. Noctua NF-A4x20 5V). In addition there is the possibility to connect a lighting (RGB). Furthermore, the following connections are available... USB-C (power supply), USB-A 3.0 (data, e.g. USB stick with music on it), main switch, QWIIC/StemmaQT (sensor) and an external 5V connector (for part 2).

The board can be produced here (AISLER) with the files (.brd and .sch) or by any other PCB manufacturer. -> https://aisler.net/

# Spec

Vin: 2.8 - 22V<br>
Vout: 5V (typ., min.4,85V, max.5,15V)<br>
Iout: 3A<br>

# Serie

- .pro

# Layout

Top<br>
![Streamer_Top_v1 2](https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/1c77e5df-f00d-4377-b685-1b03a98cbce1)

Bottom<br>
![Streamer_Bottom_v1 2](https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/7b43be1d-34f2-4312-a2fb-8e9973885202)

Routing/Dimensions(mm)<br>
![Streamer_v1 2](https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/6b37a660-d410-4483-82b9-f38904d3ce90)

Schematic<br>
Schematic as .pdf at the top of the page.

# License

Open hardware, use it, mod it, whatever you want, feel free...

# Thanks!

Own design and layout.

# Version - Build

v1.2 - 10.07.2023

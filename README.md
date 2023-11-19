# Own_RPI_Streamer_PCB

PCB files for RPI Streamer Board

# Description

This is a main board to hold a Raspberry Pi (4) and the Hifyberry Digi2 Pro expansion board. This puts the connections I need (for me) on one side to be able to build my own streamer.

- Part 1

The internal "power supply" (Pololu S13V30F5) delivers at 5V@3A, sensor and RGB are control by part 2.

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
<img src="https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/5dd89c11-b92f-4d7f-b379-6e6e650cc60d" width="15%" height="15%">

Bottom<br>
<img src="https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/8abfa396-234c-4a40-b0f2-f3d10c4c6bd4" width="15%" height="15%">

Routing/Dimensions(mm)<br>
<img src="https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/b2771dfc-d68b-4480-aa7c-dcb007886f6c" width="15%" height="15%">

Schematic<br>
Schematic as .pdf at the top of the page.

# License

Open hardware, use it, mod it, whatever you want, feel free...

# Thanks!

Own design and layout.

# Version - Build

v1.4 - 06.11.2023

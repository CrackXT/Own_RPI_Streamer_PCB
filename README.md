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
![Streamer_Top_v1 3](https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/fa4cf89e-d5a7-4cc2-a4c4-5b7617c9dc64)

Bottom<br>
![Streamer_Bottom_v1 2](https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/ddd26ace-10b6-4fae-9d76-de1fc77709cd)

Routing/Dimensions(mm)<br>
![Streamer_v1 3](https://github.com/CrackXT/Own_RPI_Streamer_PCB/assets/88975406/5e618000-e0f5-4cc4-a7af-40e821e27357)

Schematic<br>
Schematic as .pdf at the top of the page.

# License

Open hardware, use it, mod it, whatever you want, feel free...

# Thanks!

Own design and layout.

# Version - Build

v1.3 - 21.10.2023

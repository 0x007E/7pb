[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/7pb) ![Build](https://github.com/0x007e/7pb/actions/workflows/build.yml/badge.svg?branch=main) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `7PB` - 7-Phase Flasher (7-Phasenblinker)

The `7PB` project is based on a pcb with an array of transistors (`BC547`) that are constantly switching their state while driving leds with different colors.

| Experience | Level |
|:------------|:-----:|
| Soldering   | ![30%](https://progress-bar.xyz/30?progress_color=00ff00&suffix=%20Low&width=120) |
| Mechanical  | ![30%](https://progress-bar.xyz/30?progress_color=0000ff&suffix=%20Low&width=120) |

# Downloads

| Type      | File               | Description              |
|:---------:|:------------------:|:-------------------------|
| Simulation | [asc](https://github.com/0x007E/7pb/raw/refs/heads/main/7PB.asc) | LTSpice Simulation | 
| Lochmaster | [lm4](https://github.com/0x007E/7pb/raw/refs/heads/main/7PB.LM4) | Stripe grid circuit board | 
| Schematic | [pdf](https://github.com/0x007E/7pb/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/28593/main/files)     | Schematic files          |
| Board     | [pdf](https://github.com/0x007E/7pb/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/28593/main/files)     | Board file               |
| Drill     | [pdf](https://github.com/0x007E/7pb/releases/latest/download/drill.pdf) | Drill file               |
| Gerber    | [zip](https://github.com/0x007E/7pb/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/7pb/releases/latest/download/kicad.tar.gz)                | Gerber/Drill files       |
| Housing, PCB | [zip](https://github.com/0x007E/7pb/releases/latest/download/freecad.zip) / [tar](https://github.com/0x007E/7pb/releases/latest/download/freecad.tar.gz) | Housing and PCB (STEP) files     |

# Hardware

There are two parts of the hardware. The pcb and the housing of the `7PB`. The pcb is created with `KiCAD` and the housing with `FreeCAD`. All files are built with `github actions` so that they are ready for a production environment. The housing is printed with a 3D-printer (`Dremel 3D40`).

## PCB

The circuit board is populated on one side (Top). The best way for soldering is within a standard soldering system.

### Top Layer

![Top Layer](https://github.com/0x007E/7pb/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/7pb/releases/latest/download/bottom.kicad.png)

## Mechanical

The housing has a tolerance of `0.2mm` on each side of the case. So the pcb should fit perfectly in the housing. The tolerance can be modified with `FreeCAD` in the `Parameter` Spreadsheet.

### Assembled

![Assembled](./images/assembled.png)

#### Exploded

![Exploded](./images/explosion.png)

# Additional Information

| Type       | Link               | Description              |
|:----------:|:------------------:|:-------------------------|
| BC547 | [pdf](https://www.sparkfun.com/datasheets/Components/BC546.pdf) | NPN Transistor |

---

R. GAECHTER

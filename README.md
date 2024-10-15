# Riotee Module Hardware Design Files

[![Kibot ERC/DRC](https://github.com/NessieCircuits/Riotee_Module/actions/workflows/test.yml/badge.svg)](https://github.com/NessieCircuits/Riotee_Module/actions/workflows/test.yml)

The Riotee Module is a stamp-sized unit (27.2mm by 15.2mm) that can be soldered onto a user's \ac{pcb} with additional circuitry like sensors or harvesters to create deployment-ready battery-free devices quickly.
It integrates harvesting circuitry, two MCUs, an RTC, a PCB antenna, and an LED on a compact 4-layer PCB enclosed in a metal RF shield.
The module features breadboard-compatible castellated holes exposing essential signals, including 11 GPIO, two of which can also function as analog inputs.
Four additional signals on the back of the module are available when reflow-soldered onto a carrier board.

For more details and pinouts, refer to the [documentation](https://www.riotee.nessie-circuits.de/docs/latest/hardware/module.html).

Latest design files:
 - [Schematics](https://www.riotee.nessie-circuits.de/artifacts/module/latest/schematics.pdf)
 - [Layout](https://www.riotee.nessie-circuits.de/artifacts/module/latest/pcb.pdf)
 - [3D rendering](https://www.riotee.nessie-circuits.de/artifacts/module/latest/3drendering.png)
 - [Gerber](https://www.riotee.nessie-circuits.de/artifacts/module/latest/gerber.zip)
 - [BOM](https://www.riotee.nessie-circuits.de/artifacts/module/latest/bom.csv)
 - [3D step model](./resources/RioteeModule.step)
 - [Kicad schematic symbol](./resources/RioteeModule.kicad_sym)
 - [Kicad footprint](./resources/RioteeModule.pretty)

![Rendering of Riotee module](https://www.riotee.nessie-circuits.de/artifacts/module/latest/3drendering.png "Riotee module")

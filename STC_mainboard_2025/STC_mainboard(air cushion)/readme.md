# STC_mainboard(air cushion)

Brief
- STC32G128K MCU based mainboard for air cushion.

Key features
- Simple STC32G128K MCU mainboard with PWM output for controlling BLDC motor driver

Repository structure
- `extention_board.kicad_pcb` — PCB layout
- `extention_board.kicad_sch` — Schematic
- `extention_board.kicad_pro` — KiCad project file
- `extention_board.step` — 3D model export

Electrical overview (fill with measured values)
- Supply voltage: 12V - 24V

Connectors & pins
- POWER: VIN, GND
- CONTROL: PWM

Fabrication notes
- PCB thickness: 1.6 mm
- Layer count: 2
- Copper thickness: 1 oz external

BOM
- Use KiCad's BOM export (`bom` plugin) 

KiCad / development notes
- KiCad version used: 8.0

Designer
- Andy, Cheung

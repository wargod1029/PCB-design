# sensor_board

Brief
- 7 Infered sensors design for use in Forklift robot in Taiwan AERC competition

Key features
- Direct output analog signal from XH pin header

Repository structure
- `sensor_board.kicad_pcb` — PCB layout
- `sensor_board.kicad_sch` — Schematic
- `sensor_board.kicad_pro` — KiCad project file

Electrical overview (fill with measured values)
- Supply voltage: 3.3V to 5V

Connectors & pins
- POWER: VCC, GND
- SENSOR: direct analog voltage output (IR1 - IR7)

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

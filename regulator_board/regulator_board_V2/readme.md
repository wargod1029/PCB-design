# regulator_board_V2

Brief
- Second revision of the power regulator board with updated component placement and improved thermal behavior.

Key features
- Updated regulator design
- Stable output rails for downstream electronics
- KiCad schematic and PCB files included

Repository structure
- `regulator_board.kicad_pcb` — PCB layout
- `regulator_board.kicad_sch` — Schematic
- `regulator_board.kicad_pro` — KiCad project file

Electrical overview (fill with measured values)
- Input voltage range: <e.g. 9–24 V>
- Output rails: <e.g. 5 V, 3.3 V>
- Current capacity: <A>

Connectors & pins
- INPUT: VIN, GND
- OUTPUT: VOUT, GND
- CONTROL: optional enable or sense pins

Fabrication notes
- PCB thickness: 1.6 mm
- Layer count: 2
- Copper thickness: 1 oz external

BOM
- Use KiCad's BOM export (`bom` plugin) to generate an initial parts list.

KiCad / development notes
- KiCad version used: 8.0

Designer
- Andy, Cheung

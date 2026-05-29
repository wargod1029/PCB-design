# STC_mainboard_V2 (BLDC)

Brief
- Second version of the STC BLDC mainboard. Includes updated BLDC control circuits and a 3D model export.

Key features
- BLDC motor control mainboard
- KiCad schematic, PCB, and 3D model files
- Designed for system integration with other STC boards

Repository structure
- `STC_mainboard.kicad_pcb` — PCB layout
- `STC_mainboard.kicad_sch` — Schematic
- `STC_mainboard.kicad_pro` — KiCad project file
- `STC_mainboard.step` — 3D model export

Electrical overview (fill with measured values)
- Supply voltage: <e.g. 12–24 V>
- BLDC phase outputs and control rails
- Recommended current capacity

Connectors & pins
- POWER: VIN, GND
- BLDC MOTOR: three phase outputs
- CONTROL: PWM, EN, comms

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
- Andy, Cheung

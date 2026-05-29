# STC_BLDC_ESC

Brief
- BLDC electronic speed controller board using STC MCU. Intended for aircushion smart car race and drone motor control.

Key features
- BLDC motor driving

Repository structure
- `STC_ESC.kicad_pcb` — PCB layout
- `STC_ESC.kicad_sch` — Schematic
- `STC_ESC.kicad_pro` — KiCad project file
- `lib/` — local symbols and footprints

Electrical overview (fill with measured values)
- Supply voltage: 12V - 24V
- Current rating: <10A>

Connectors & pins
- POWER: VIN, GND
- MOTOR: three phase outputs
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
- Jason, CHEN and Andy, Cheung



# DRV Motor Driver

Brief
- DRV_motordriver is a brushed motor driver board based on the DRV8701. It provides PWM speed control and enable/disable control for a single motor H-bridge. This README documents usage, test procedures, and maintenance notes — edit the placeholders below with measured/confirmed values.

Key features
- DRV8701-based H-bridge for brushed motors
- PWM speed control (center-zero style: 50% ≈ stop; >50% forward; <50% reverse)
- Enable pin for safe power-up and shutdown

Repository structure
- `DRV_motordriver.kicad_pcb` — PCB layout
- `DRV_motordriver.kicad_sch` — Schematic
- `DRV_motordriver.kicad_pro` — KiCad project file
- `datasheet/` — component datasheets and reference designs
- `lib/` — local symbols & footprints

Electrical overview (fill with measured values)
- Supply voltage (VIN): <e.g. 6–24 V> — confirm actual range
- Recommended motor current limit: <A>
- Fuses / protection: <type/value>

Connectors & pins
- POWER: VIN, GND
- MOTOR: M+, M-
- CONTROL: `PWM` (speed/direction), `EN` (enable), `GND` (signal ground)
- See schematic for exact net names and connector pinouts.

Fabrication notes
- PCB thickness: 1.6 mm (confirm)
- Layer count: 2
- External copper: 1 oz (confirm)
- If you need controlled impedance or internal planes, note that in fabrication files.

BOM
- Use KiCad's BOM export (`bom` plugin) to generate an initial parts list.

KiCad / development notes
- KiCad version used: 8.0
- Local libraries: `lib/DRV8701PRGER` — import instructions are in the `how-to-import.htm` files if needed.

Designer
- Andy, Cheung


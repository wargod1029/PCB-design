# dual_motor_driver

Brief
- Dual brushed motor driver board using BTS7960b half bridge IC. Designed for large power motor (24V, 15A)

Key features
- Two-channel motor drive
- PWM speed control for both motors

Repository structure
- `motor_driver_2.kicad_pcb` — PCB layout
- `motor_driver_2.kicad_sch` — Schematic
- `motor_driver_2.kicad_pro` — KiCad project file

Electrical overview (fill with measured values)
- Supply voltage: <12–24 V>
- Recommended motor current limit: <15A>

Connectors & pins
- POWER: VIN, GND, 
- MOTOR A: M1+, M1-
- MOTOR B: M2+, M2-
- CONTROL: `PWM_1A`, `PWM_1B`, `PWM_2A`, `PWM_2B`, `EN1`, `EN2`


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
# motor_driver_v7

Brief
- Motor driver version 7 board for dynamic motor control. Including voltage regulator to 5V and 3.3V

Key features
- Motor driver by BTS7960B half bridge IC
- voltage regulator to 5V by Buck convertor (TPS54360DDAR)
- Voltage regulator to 3.3V by Low dropout regualtor

Repository structure
- `motor_driver_2.kicad_pcb` — PCB layout
- `motor_driver_2.kicad_sch` — Schematic
- `motor_driver_2.kicad_pro` — KiCad project file

Electrical overview (fill with measured values)
- Supply voltage: 8V - 24V
- Motor current limit: 15A


Connectors & pins
- POWER: VIN, GND
- MOTOR: M+, M-
- CONTROL: PWM, EN, GND

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

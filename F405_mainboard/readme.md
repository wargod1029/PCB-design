# F405_mainboard

Brief
- F405 mainboard based on the STM32F405 MCU platform, intended for teaching purpose in robot design contest hosted by HKUST Robotics team

Key features
- STM32F405-based main controller board
- Peripheral connectors available for sensors, power, and communications

Repository structure
- `RDC.kicad_pcb` — PCB layout
- `RDC.kicad_sch` — Schematic
- `RDC.kicad_pro` — KiCad project file

Electrical overview (fill with measured values)
- Supply voltage: 12V 

Connectors & pins
- POWER: VIN, 5V, 3.3V, GND
- I/O: UART, I2C, SPI, PWM, ADC pins, most of the GPIO pins

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

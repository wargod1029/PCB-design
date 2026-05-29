
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

Quick start (safety first)
1. With no motor connected, power the board and verify VIN and GND rails (measure with multimeter).
2. Confirm `EN` is held low (disabled) before connecting the motor.
3. Connect a small test motor or current-limited supply.
4. Apply a low-duty PWM signal (~55%) and confirm motor rotates slowly in the expected direction.
5. Sweep duty up/down to confirm forward and reverse behavior.

Testing & verification
- Smoke test: power up with no load and check for overheating or excessive current draw.
- Output verification: measure H-bridge outputs with an oscilloscope or multimeter while applying PWM.
- Functional test: run motor at several duty cycles and verify temperature, vibration, and current.

Fabrication notes
- PCB thickness: 1.6 mm (confirm)
- Layer count: 2
- External copper: 1 oz (confirm)
- If you need controlled impedance or internal planes, note that in fabrication files.


BOM
- Use KiCad's BOM export (`bom` plugin) to generate an initial parts list.

KiCad / development notes
- KiCad version used: 8.0 (replace if different)
- Local libraries: `lib/DRV8701PRGER` — import instructions are in the `how-to-import.htm` files if needed.

Known issues & troubleshooting
- Symptom: Right-side driver reports ~50% output and motor does not run.
	- Check solder joints on the DRV and MOSFETs (reflow suspected bad joints).
	- Verify gate drive supply voltages and sense resistor connections.
	- Measure continuity from DRV outputs to MOSFET gates and MOSFET drains/sources.
	- Swap components (if available) to isolate a bad device.

Revision history
- v0.1 — Initial files and prototype
- v0.2 — [date] — Notes: <fill in changes after testing>

Contributors
- Andy Cheung

Next steps / TODO
- Run a full reflow and re-test the suspected failing side.



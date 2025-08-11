# Auto Watering PCB

![PCB view](pcb.webp)

KiCad project for auto watering PCB.
This PCB is designed for up to 6 valves.

This KiCad project requires Espressif KiCad Library.

You can find a firmware designed to run on this board [on the dedicated repository](https://github.com/auto-watering/firmware).

## Required parts

- ESP32 DevKit C
- Support for ESP32 board
- For each valve:
  - SRD12VDC relay
  - PC817 C photocoupler
  - LED
  - JST connector 1x02 2.50mm pitch (for case mounted LED)
  - 1 kOhm resistor
  - 56 Ohm resistor
  - flyback diode
  - TerminalBlock Phoenix MKDS-1,5/2 1x02 5mm pitch (for valve)
  - Valves themselves (for example RainBird HV series, 24VAC)
- 5V DC power supply for ESP32
- 12V DC power supply for relays command
- Power supply for valves (24VAC for RainBird HV series)
- 3x TerminalBlock Phoenix MKDS-1,5/2 1x02 5mm pitch (for power supplies)


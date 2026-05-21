# Rocket-Flight-Controller-RFC-PCB
Custom Raspberry Pi Pico based Flight Controller PCB designed for model rockets, experimental aerospace systems, avionics testing, and embedded control applications.
# Rocket Flight Controller

Custom Raspberry Pi Pico based flight controller PCB for model rockets and embedded aerospace systems.

## Features

- RP2040 / Raspberry Pi Pico based
- 6 PWM servo outputs
- GPS interface
- IMU + BMP sensor interface
- RGB status LEDs
- Buzzer
- Voltage monitoring
- External servo power input
- On-board voltage regulation

## Hardware

- Raspberry Pi Pico
- AMS1117-5.0
- AMS1117-3.3
- RGB LEDs
- Piezo buzzer
- Screw terminals
- Servo headers

## Interfaces

| Interface | Purpose |
|---|---|
| PWM | Servo control |
| I2C | IMU / BMP sensors |
| UART | GPS module |
| ADC | Battery monitoring |

## Applications

- Rocket avionics
- Recovery systems
- Flight telemetry
- Sensor testing
- Embedded control projects

## PCB

- Designed in KiCad 8
- 2-layer PCB
- Black solder mask
- Compact layout

## Future Improvements

- LoRa telemetry
- SD card logging
- Pyro channels
- Wireless telemetry
- High-G IMU support

## Repository Structure

```text
hardware/
firmware/
docs/
README.md

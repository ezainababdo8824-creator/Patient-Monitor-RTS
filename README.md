# Patient Monitor - Real-Time Systems

A real-time scheduling project for a patient monitoring system using ESP32 and FreeRTOS.

## Task Parameters

| Task | Execution Time (C) | Period (T) |
|---|---:|---:|
| Heart | 1 ms | 4 ms |
| Oxygen | 3 ms | 8 ms |
| Alarm | 4 ms | 20 ms |
| Display | 6 ms | 40 ms |

## Wokwi Simulation

[Open the ESP32 project on Wokwi](https://wokwi.com/projects/481303278423657473)

## Project Files

- `lab08-template.ino` — FreeRTOS scheduling implementation.
- `diagram.json` — Wokwi circuit configuration.

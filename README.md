# ESP32 Radar System

Ultrasonic radar using HC-SR04 + servo sweep with real-time visualization.

## How it works
Mounts HC-SR04 on a servo motor. Servo sweeps 0–180°, measuring distance at each angle. Data sent over Serial to a Processing sketch that renders a radar-style display.

## Components
- ESP32 Dev Board
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor

## Wiring
| Component    | ESP32 Pin |
|--------------|-----------|
| TRIG         | GPIO 5    |
| ECHO         | GPIO 18   |
| Servo signal | GPIO 25   |

## Visualization
Open the Processing sketch to see the live radar display on your computer.

## Part of
[EC Simplified](https://github.com/maruthirm333-prog/ec-simplified) — ESP32 Zero to Pro series

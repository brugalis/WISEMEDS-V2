# WISEMEDS V2 Hardware Documentation

## System Overview

WISEMEDS V2 uses an ESP32 microcontroller as the main controller for an automated medication dispensing system.

The ESP32 controls:

- Servo dispensing mechanism
- Buzzer notification
- LED status indicator
- Manual dispense button
- WiFi/Firebase communication


---

# Hardware Components

| Component | Quantity | Purpose |
|---|---:|---|
| ESP32 Dev Module | 1 | Main controller |
| Servo Motor | 1 | Medication dispensing mechanism |
| Active Buzzer | 1 | Audio notification |
| LED | 1 | System status indicator |
| Push Button | 1 | Manual dispensing |
| Breadboard | 1 | Circuit assembly |
| Jumper Wires | Several | Connections |


---

# ESP32 Pin Connections

## Servo Motor

| Servo Wire | ESP32 |
|---|---|
| Signal (Yellow/Orange) | GPIO 18 |
| VCC (Red) | 5V |
| GND (Brown/Black) | GND |


---

## Buzzer

| Buzzer Pin | ESP32 |
|---|---|
| Positive (+) | GPIO 26 |
| Negative (-) | GND |


---

## LED Indicator

| LED Pin | ESP32 |
|---|---|
| Positive (+) through resistor | GPIO 2 |
| Negative (-) | GND |


---

## Manual Dispense Button

| Button Pin | ESP32 |
|---|---|
| Pin 1 | GPIO 27 |
| Pin 2 | GND |

The ESP32 uses:

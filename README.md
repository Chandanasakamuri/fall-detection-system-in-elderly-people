# Fall Detection System for Elderly People 👵🏼🧓🏼

A smart and affordable system designed to detect falls in elderly individuals using sensors, Arduino, and NodeMCU. The system instantly sends alerts to guardians or caretakers when a fall is detected, helping reduce response time and ensuring safety.

## 🚀 Project Overview

This project aims to develop a real-time fall detection system that:
- Detects sudden falls using accelerometer and gyroscope sensors.
- Processes signals via Arduino Uno.
- Sends alert notifications to registered guardians using NodeMCU.
- Minimizes response time during emergency situations.

## 🛠 Technologies Used

| Arduino Uno | Sensor data processing |
| NodeMCU | Wi-Fi module to send alert |
| Motion Sensor | Detects fall motion |
| Buzzer / LED | Alert indication |
| C/C++ (Arduino IDE) | Programming the microcontrollers |

## 📲 How It Works

1. Sensor detects a rapid fall (based on sudden acceleration).
2. Arduino processes the input and classifies it as a fall or normal motion.
3. If a fall is detected, it triggers NodeMCU.
4. NodeMCU sends an alert message to the guardian's phone/email via internet.
5. Optional: A buzzer or LED indicates a fall locally.

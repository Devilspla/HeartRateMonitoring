#Heart Rate Monitoring System
This repository contains the source code, circuit diagram, and required libraries for an Arduino-based Heart Rate Monitoring System. The system uses a pulse sensor to measure heart rate in real-time and displays it on an LCD. This project is ideal for beginners exploring Arduino and electronics.

#Features
Real-time heart rate monitoring.
Displays heart rate on a 16x2 LCD screen.
Outputs data via the Arduino Serial Monitor for debugging.
Simple and easy-to-assemble circuit.

#Repository Contents
src/: Contains the source code file (heartbeat.ino).
libraries/: Includes the required library files for the project:
NewliquidCrystal_1.3.4.zip
NewliquidCrystal_i2c.zip
assets/: Contains supporting media, such as:
Circuit diagram.png: Visual representation of the circuit.
README.md: Project documentation.

#Requirements
Hardware
Arduino UNO (or compatible microcontroller)
Pulse Sensor
16x2 LCD (with I2C adapter recommended)
wires
Software:
Arduino IDE (Version 1.8.0 or later)
Required libraries (included in this repository under libraries/):
NewliquidCrystal library

#How It Works
1.The pulse sensor detects heartbeat signals and sends analog data to the Arduino.
2.The Arduino processes the signal and calculates the heart rate in beats per minute (BPM).
3.The calculated BPM is displayed on the LCD and optionally logged to the Serial Monitor.

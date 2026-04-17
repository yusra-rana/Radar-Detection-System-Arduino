# 📡 Radar Detection System

An Arduino-based Radar Detection System that detects position and 
distance of objects using an Ultrasonic Sensor and Servo Motor.

## 🏫 Project Info
- **University:** Fatima Jinnah University, Rawalpindi
- **Course:** Digital Logic & Design (DLD)
- **Semester:** 2nd Semester 2025

## 📋 Features
- 🔄 **360° Scanning** — Servo motor rotates ultrasonic sensor
- 📏 **Distance Detection** — Detects objects from 2 to 40 cm
- 📐 **Angle Detection** — Shows exact angle of detected object
- 🖥️ **LCD Display** — Shows real-time angle & distance
- 🎯 **GUI Radar Display** — Visual radar screen using Processing

## 🛠️ Hardware Components
- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- LCD Display (I2C)
- Breadboard & Jumper Wires

## 💻 Software Used
- **Arduino IDE** — For Arduino code
- **Processing** — For GUI radar display

## 🔌 Pin Configuration
| Component | Arduino Pin |
|-----------|------------|
| Ultrasonic Trig | D9 |
| Ultrasonic Echo | D10 |
| Servo Motor | D6 |
| LCD (I2C) | SDA/SCL |

## 🚀 How to Run
1. Connect hardware as per pin configuration
2. Upload `radar.ino` to Arduino using Arduino IDE
3. Open Processing and run `radar.pde`
4. Watch the radar scan and detect objects!

## 🎥 Demo
Watch the demo video in the repository!

## 📁 Project Files
- `radar.ino` — Arduino source code
- `radar.pde` — Processing GUI code
- `Report.pdf` — Complete project report
- `demo.mp4` — Project demo video

---
⭐ If you like this project, give it a star!

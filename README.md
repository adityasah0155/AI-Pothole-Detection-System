# AI-Based Real-Time Pothole Detection, Geolocation and Automated Road Damage Reporting System

## 📌 Project Overview

This project is an AI-based road condition monitoring system designed to detect potholes in real time, identify their geographical location, analyze road damage severity, and generate automated road damage reports.

The system combines computer vision, GPS, motion sensing, IoT communication, and a web-based dashboard.

## 🎯 Objectives

- Detect potholes using AI/YOLO
- Capture road images/video using ESP32-CAM
- Record pothole location using GPS
- Analyze vehicle vibration using MPU6050
- Estimate pothole severity
- Store detection and location data
- Display potholes on a dashboard/map
- Allow registered users to confirm or reject detections
- Generate road damage reports for authorities

## 🔄 System Flow

Road → ESP32-CAM → Wi-Fi → AI/YOLO Detection → GPS Location → MPU6050 Analysis → Severity Analysis → Database → Dashboard → User Verification → Authority Report

## 🔧 Hardware

- ESP32-CAM
- NEO-6M GPS Module
- MPU6050 Accelerometer/Gyroscope
- 18650 Li-ion Battery
- TP4056 Charging Module
- MT3608 Boost Converter
- USB Type-C Charging Input
- Breadboard / PCB
- Jumper Wires
- Buzzer / LED (optional)

## 💻 Software

- Python
- OpenCV
- YOLO
- Arduino IDE
- Database
- Web Dashboard
- EasyEDA

## 🤖 AI Component

The AI model processes road images/video and detects potholes.

The ESP32-CAM is used for image capture and communication, while AI inference is performed on a laptop/server.

## 📍 Location & Severity

For each detected pothole, the system can record:

- Latitude
- Longitude
- Detection time
- AI confidence
- Acceleration/vibration data
- Estimated severity

## 🔋 Power System

USB-C → TP4056 → 18650 Battery → MT3608 Boost Converter → 5V Output → ESP32-CAM

## 🖥️ PCB

The custom PCB was designed using EasyEDA.

The PCB integrates the power and sensor connections required for the prototype.

## 🌍 Sustainable Development Goals

### SDG 9
Industry, Innovation and Infrastructure

### SDG 11
Sustainable Cities and Communities

### SDG 3
Good Health and Well-Being

## 🚀 Future Scope

- Real municipal authority integration
- Cloud-based deployment
- Mobile application
- Multi-vehicle monitoring
- Automatic repair-status tracking
- Road damage history and analytics
- Improved pothole severity estimation

## 📂 Project Backup

The EasyEDA PCB and schematic source files are included in this repository as a backup.

## 👥 Team

This project is developed as a 3-member academic team.

### Project Status

🚧 Prototype / Academic Project

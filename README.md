# IoT-Based Fall Detection & Emergency Alert System

## 📌 Overview
This project is a wearable IoT system that detects falls and sends real-time alerts with location.

## ⚙️ Hardware Used
- ESP32
- MPU6050 (Accelerometer + Gyroscope)
- NEO-6M GPS Module

## 🚀 Features
- Real-time fall detection
- GPS-based location tracking
- Automatic Telegram alert system
- Low-cost and portable

## 🧠 Working
1. MPU6050 detects motion
2. ESP32 processes data
3. Fall is detected using multi-stage algorithm
4. GPS retrieves location
5. Alert sent via Telegram

## 📷 Prototype
![Prototype](images/prototype.jpg)

## 🔧 Setup Instructions

### 1. Install Libraries
- Adafruit MPU6050
- TinyGPS++
- WiFi

### 2. Configure
Update in code:

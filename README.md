# Smart-Agriculture-Monitoring-System
# 🌱 Smart Agriculture Monitoring System

A microcontroller-based smart agriculture system that monitors **soil moisture**, **light intensity**, and **distance** using multiple sensors and displays real-time data on a **Nokia 5110 LCD**.

---

## 📌 Project Overview

This project is designed to help farmers monitor field conditions efficiently using embedded systems. It integrates multiple sensors with a **TIVA ARM Cortex-M4 microcontroller** to provide real-time feedback and alerts.

---

## 🧰 Components Used

- TIVA ARM Cortex-M4 Microcontroller
- Soil Moisture Sensor
- LDR (Light Dependent Resistor)
- Ultrasonic Sensor
- Nokia 5110 LCD Display
- Buzzer
- LED
- Connecting Wires & Power Supply

---

## ⚙️ Key Features

- Real-time soil moisture monitoring
- Light detection using LDR
- Distance measurement using ultrasonic sensor
- Visual output on Nokia 5110 LCD
- Alert indication using buzzer and LED
- Low-power embedded system design

---

## 🧠 Sensor Description

### 🌞 LDR Sensor
- Detects light intensity
- Resistance decreases as light increases
- Used for light detection and alert system

### 🌊 Soil Moisture Sensor
- Measures water content in soil
- Helps determine whether soil is dry or wet

### 📏 Ultrasonic Sensor
- Measures distance using ultrasonic sound waves
- Used for object proximity detection

---

## 🖥️ Display Unit

**Nokia 5110 LCD**
- 84 × 48 pixel monochrome display
- Low power consumption
- Displays sensor data clearly

---

## 💻 Code

The complete Arduino-compatible code is available in the `code/` folder.

Main functionalities:
- Ultrasonic distance calculation
- LDR-based light detection
- Soil moisture analysis
- LCD output display
- Serial monitor debugging

---

## 📤 Output

- Distance displayed in centimeters
- Soil condition (Dry / Wet)
- Light detection alert
- Visual output on LCD and LED indication

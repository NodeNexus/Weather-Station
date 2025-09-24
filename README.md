# 🌦️ Arduino Weather Station

## 📌 Overview
This project builds a simple **weather station** using Arduino, a **BME280 sensor**, and an **LCD display**.  
It shows **temperature, humidity, and pressure** in real-time.

---

## 🛠️ Hardware Required
- Arduino Uno/Nano  
- BME280 Sensor (I2C)  
- LCD Display (16x2, I2C module recommended)  
- Jumper wires, breadboard  

---

## 🔌 Wiring
- **BME280 → Arduino**  
  - VCC → 3.3V  
  - GND → GND  
  - SDA → A4  
  - SCL → A5  

- **LCD → Arduino**  
  - VCC → 5V  
  - GND → GND  
  - SDA → A4  
  - SCL → A5  

---

## ▶️ Usage
1. Install **Adafruit BME280** and **Adafruit Unified Sensor** libraries from Arduino IDE Library Manager.  
2. Install **LiquidCrystal_I2C** library.  
3. Upload the sketch to Arduino.  
4. Read live temperature, humidity, and pressure on LCD + Serial Monitor.  

---

## 📂 Repo Structure

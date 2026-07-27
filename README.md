# 🌡️ Smart Environment Monitoring System

![STM32](https://img.shields.io/badge/STM32-Blue?style=for-the-badge)
![Embedded C](https://img.shields.io/badge/Language-Embedded%20C-blue?style=for-the-badge)
![Sensors](https://img.shields.io/badge/Sensors-DHT11%20%7C%20MQ2-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)

An embedded system designed to continuously monitor environmental conditions such as temperature, humidity, and gas leakage. The system displays live sensor readings on an LCD and activates a buzzer whenever gas concentration exceeds the safety threshold.

---

## 📹 Project Demonstration

<p align="center">
<img src="media/demo.gif" width="700">
</p>

🎥 **Full Demo:** [Watch Video](media/demo.mp4)

---

## 📌 Project Specifications

| Category | Details |
|-----------|---------|
| Microcontroller | STM32F407VG |
| Programming Language | Embedded C |
| IDE | STM32CubeIDE |
| Temperature Sensor | DHT11 |
| Gas Sensor | MQ-2 |
| Display | 16x2 LCD (I2C) |
| Alert System | Buzzer |
| Communication | I2C |

---

## ✨ Features

- 🌡️ Real-time Temperature Monitoring
- 💧 Humidity Monitoring
- 🔥 Gas Leakage Detection
- 📺 LCD Display
- 🚨 Automatic Buzzer Alert
- ⚡ Low Power Embedded Design

---

## 🛠 Components Used

| Component | Quantity |
|-----------|---------|
| STM32F407VG | 1 |
| DHT11 Sensor | 1 |
| MQ-2 Gas Sensor | 1 |
| 16x2 I2C LCD | 1 |
| Buzzer | 1 |
| Breadboard | 1 |
| Jumper Wires | As required |

---

## 🔌 Pin Connections

| STM32 Pin | Component |
|------------|-----------|
| PB6 | LCD SCL |
| PB7 | LCD SDA |
| PA1 | MQ-2 Analog Output |
| PA0 | DHT11 Data |
| PA8 | Buzzer |

---

## 📸 Project Gallery

(Add project screenshots here)

---

## 🧠 How It Works

1. STM32 continuously reads temperature and humidity from the DHT11 sensor.
2. MQ-2 detects smoke and gas concentration.
3. Live values are displayed on the LCD.
4. When gas exceeds the predefined threshold, the buzzer is activated.
5. Monitoring continues continuously in real time.

---

## 📚 What I Learned

- STM32 Peripheral Programming
- I2C Communication
- Sensor Interfacing
- ADC Programming
- Real-time Embedded Systems
- Debugging Embedded Applications

---

## ⚠️ Challenges Faced

- Calibrating the MQ-2 sensor.
- Reading DHT11 accurately.
- Display synchronization.
- Noise reduction in analog sensor readings.

---

## 🚀 Future Improvements

- IoT Dashboard
- Mobile Notifications
- SD Card Data Logging
- Cloud Integration
- Battery Backup

---

## 🎯 Key Takeaways

This project enhanced my understanding of sensor interfacing, real-time embedded programming, and hardware-software integration using STM32. It strengthened my debugging skills and gave me practical experience in building reliable environmental monitoring systems.

# EV-ADAS-System-Telemetry-Dashboard

An Advanced Driver Assistance System (ADAS) and Electric Vehicle (EV) telemetry monitoring simulation built using an **STM32 Microcontroller**, **PICSimLab**, and a **Real-time Web Dashboard**.

---

## 🚀 Features

### **1. EV Telemetry & Performance**
- **Speed Monitoring:** Real-time speedometer display and historical logging.
- **Battery Management (SOC):** Live State-of-Charge percentage bar and estimated driving range.
- **Powertrain Metrics:** Motor torque tracking, acceleration/braking pedal inputs, and motor temperature monitoring.

### **2. ADAS & Safety Features**
- **Collision Avoidance (COL):** Front ultrasonic sensor tracking with Time-to-Collision (TTC) calculations.
- **Blind Spot Detection (BSD):** Left and right sensor warnings.
- **Alarm Priority Management:** Visual and terminal alert priority states for driver safety.

---

## 🛠️ Tech Stack & Tools

- **Firmware:** C Language (Developed using STM32CubeIDE with HAL drivers)
- **Simulation:** PICSimLab (Virtual hardware simulation with STM32 Blue Pill and ultrasonic sensors)
- **Dashboard Interface:** HTML, CSS, JavaScript (Real-time telemetry UI)
- **Communication:** UART / Virtual Terminal (`115200` baud rate)

---

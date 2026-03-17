# self-balancing-robot-esp32
A self-balancing robot built with an ESP32, using an MPU6050 IMU for tilt sensing and PID control for stability. The project includes motor driver control, and tunable PID parameters for balance adjustment.
# Two-Wheel Self-Balancing Robot (ESP32 + MPU6050)

A robotics project demonstrating an inverted pendulum system stabilized using a PID controller.
The robot uses an ESP32 microcontroller, an MPU6050 IMU, and a custom motor controller library.

---

## ✨ Features
- Real-time balancing using PID control
- MPU6050 DMP (Digital Motion Processor) for accurate tilt estimation


---

## 📂 Repository Structure
- `src/` → Arduino/ESP32 source code (`main.ino`, motor controller library)
- `docs/` → Full report PDF, images, and SolidWorks models
- `hardware/` → Circuit schematics, wiring diagrams, PCB/perfboard layout

---

## 🛠️ Hardware Used
- **ESP32 Doit Dev V1**
- **MPU6050 6-axis IMU**
- **L2983D Motor Driver** 
- **DC Gear Motors + Wheels**
- **Li-ion Battery Pack**
- **cardboard frame**

---

## ⚙️ Software & Libraries
- [Arduino PID Library](https://playground.arduino.cc/Code/PIDLibrary/)
- [I2Cdev + MPU6050 DMP](https://github.com/jrowberg/i2cdevlib)

---



📖 Documentation
The full report is available here 
 - [self-balance-robot](https://github.com/ShenYiTan/self-balancing-robot-esp32/blob/main/docs/self-balance.pdf)

---

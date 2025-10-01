# self-balancing-robot-esp32
A self-balancing robot built with an ESP32, using an MPU6050 IMU for tilt sensing and PID control for stability. The project includes motor driver control, Bluetooth communication, and tunable PID parameters for balance adjustment.
# Two-Wheel Self-Balancing Robot (ESP32 + MPU6050)

A robotics project demonstrating an inverted pendulum system stabilized using a PID controller.
The robot uses an ESP32 microcontroller, an MPU6050 IMU, and a custom motor controller library.

---

## ✨ Features
- Real-time balancing using PID control
- ESP32 with built-in WiFi/Bluetooth for future expansion
- MPU6050 DMP (Digital Motion Processor) for accurate tilt estimation
- Custom LMotorController library for PWM-based motor control
- Documented step-by-step build process (mechanical, electronic, and software)

---

## 📂 Repository Structure
- `src/` → Arduino/ESP32 source code (`main.ino`, motor controller library)
- `docs/` → Full report PDF, images, and SolidWorks models
- `hardware/` → Circuit schematics, wiring diagrams, PCB/perfboard layout

---

## 🛠️ Hardware Used
- **ESP32 Development Board**
- **MPU6050 6-axis IMU**
- **L298N Motor Driver** (or equivalent H-bridge)
- **DC Gear Motors + Wheels**
- **12V Li-ion Battery Pack**
- **3D-printed / custom frame**

---

## ⚙️ Software & Libraries
- [Arduino PID Library](https://playground.arduino.cc/Code/PIDLibrary/)
- [I2Cdev + MPU6050 DMP](https://github.com/jrowberg/i2cdevlib)

---



📖 Documentation
The full report is available here 
[self-balance-robot]([https://github.com/jrowberg/i2cdevlib](https://github.com/ShenYiTan/self-balancing-robot-esp32/blob/main/docs/self-balance.pdf))


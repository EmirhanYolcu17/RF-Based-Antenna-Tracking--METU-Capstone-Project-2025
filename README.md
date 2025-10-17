# RF-Based-Antenna-Tracking--METU-Capstone-Project-2025
# RF-based Antenna Tracking System (RFATS)

**Capstone Project — Middle East Technical University (METU) Electrical and Electronics Engineering**  
**Project Period:** September 2024 – May 2025  
**Team:** Alkım Bozkurt, Emirhan Yolcu, Sevda Sıla Yıldız, Özgür Akyaz, Bora Özkan  
**Supervisors:** METU EEE Design Studio – Section 4  

---

## 🎥 Project Videos / Demonstrations

- **Main Introduction Video**: https://youtu.be/4yAlRrQ7uTo  
- **Short Demo Videos**:  
  - https://youtube.com/shorts/r1stuInhEX4?feature=share  
  - https://youtube.com/shorts/zlODQm8vasA?feature=share  
  - https://youtube.com/shorts/vQwEJDtw4PE?feature=share  
  - https://youtube.com/shorts/FbdIFisBS-A?feature=share  

---

## 📡 Overview

The **RF-based Antenna Tracking System (RFATS)** is a real-time directional tracking platform designed to maintain reliable wireless communication with mobile transmitters in **GPS-denied or jamming-prone environments**.  

The system estimates the **direction of arrival (DoA)** of RF signals through phase difference analysis between two directional antennas and continuously aligns the antenna orientation in **azimuth and elevation** to preserve signal lock.  

This project integrates **signal processing, control systems, and mechanical design** into a compact, modular, and fully embedded real-time system.

---

## ⚙️ System Architecture

The system consists of five main subsystems:

1. **Transmitting Antenna Module** – Generates RF signals serving as the mobile source.  
2. **Receiving Antenna Module** – Captures and switches directional signals via hybrid Yagi–Vivaldi setup.  
3. **Processing Unit** – Executes C++ signal processing on **Raspberry Pi 5**, performing DoA estimation using the **Root-MUSIC algorithm**.  
4. **Motor Control Unit** – Uses **Arduino Uno** and **TB6600 driver** to steer a **NEMA 23 stepper motor** (azimuth) and **DC motor** (elevation).  
5. **Power System** – Powered by a 3-cell 2800 mAh Li-Po battery with over-discharge protection.

A full system explanation, hardware schematics, and test results are documented in the PDF report below.

---

## 📄 Report

👉 **[Critical Design Review Report (PDF)](./Critical%20Design%20Review%20Report%20Dalgona.pdf)**  
This document covers:
- Requirement and system-level design  
- Subsystem integration and synchronization  
- Hardware selection and power analysis  
- Test procedures and performance results  
- Cost, schedule, and trade-off evaluations  

---

## 🧠 Key Features

- Real-time RF-based direction finding without GPS  
- 360° azimuth and unrestricted elevation tracking  
- Dual-controller structure for precise and stable motion  
- Modular architecture allowing subsystem upgrades  
- Developed fully in **C++**, **Arduino**, and **C# GUI**

---

## 🏆 Achievements

- **1st Place — 2025 METU EEE Capstone Project Competition**  
- Completed design, hardware fabrication, and validation within a 9-month project cycle.  
- Demonstrated robust tracking performance under controlled laboratory conditions.

---

## 🔗 References

- [Analog Devices ADALM-PLUTO SDR](https://www.analog.com/en/products/adalm-pluto.html)  
- [Raspberry Pi 5 Documentation](https://datasheets.raspberrypi.com/rpi5/raspberry-pi-5-product-brief.pdf)  
- [TB6600 Stepper Driver Datasheet](https://toshiba.semicon-storage.com)  

---

📬 *For inquiries:*  
Sevda Sıla Yıldız – [LinkedIn](https://www.linkedin.com/) | sevda.silayildiz@example.com  

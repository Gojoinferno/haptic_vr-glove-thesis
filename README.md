Development and Evaluation of an Affordable VR Glove with Force Feedback and IMU Tracking

📌 Overview

This repository contains the implementation and documentation for my Master's Thesis at Ulm University.

The project focuses on designing and evaluating a **low-cost VR haptic glove** with:

* Force feedback using servo motors
* Finger tracking using potentiometers
* Hand orientation tracking using IMUs (MPU6050 & ICM20948)
* Wireless communication via ESP32

The goal is to provide an **affordable alternative to commercial VR gloves** for applications like medical training.

---

🎯 Features

* Low-cost DIY haptic glove design
* IMU-based orientation tracking (6 DoF & 9 DoF comparison)
* Quaternion-based sensor fusion (no gimbal lock)
* Complementary and Kalman filter implementation
* Integration with SteamVR (OpenGloves)

---

🛠️ Hardware Components

* ESP32-WROOM-32
* MPU6050 (6 DoF IMU)
* ICM20948 (9 DoF IMU)
* MG90S Servo Motors
* Potentiometers (finger tracking)
* 3D printed parts

---

⚙️ Software & Technologies

* C++ (ESP32 firmware)
* Sensor Fusion Algorithms:

  * Complementary Filter
  * Kalman Filter
  * Quaternion-based fusion
* OpenGloves framework
* SteamVR integration

---

📊 Results Summary

* ICM20948 outperforms MPU6050 in accuracy and latency
* Quaternion & Kalman filters provide best performance
* IMU-based tracking is feasible but shows drift vs Vive Tracker
* Low latency (~20ms) makes system usable for VR



👨‍🎓 Author

**Chiranthan Mahadeva**
M.Sc. Computer Science
Ulm University




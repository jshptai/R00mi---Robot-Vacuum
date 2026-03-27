# Roomi: Autonomous Smart Vacuum with App-Based Voice Command Control
### BSCpE Capstone Project | Southern Philippines Institute of Science & Technology

**Roomi** is an advanced robotic vacuum system designed to provide a highly autonomous and accessible cleaning solution. Developed by Computer Engineering students, it integrates **LiDAR-assisted mapping** and **Voice Command integration** to address the limitations of traditional robotic vacuums, such as inefficient navigation and complex manual controls.

---

## 🚀 Key Features
* **SLAM-Based Navigation:** Utilizes Simultaneous Localization and Mapping (SLAM) for real-time path planning and environmental awareness.
* **LiDAR-Assisted Mapping:** Employs an LD06 LiDAR sensor for precise 360-degree distance measurement and 2D mapping (up to a 12-meter range).
* **Voice Command Control:** Features an intuitive Android application that allows users to operate the vacuum via voice commands (e.g., "Start," "Stop"), enhancing accessibility for those with limited mobility.
* **Adaptive Obstacle Detection:** A hybrid sensor array (LiDAR, Ultrasonic, and IR) allows the robot to navigate complex indoor layouts and avoid dynamic obstacles.
* **Automated Power Management:** Includes a dedicated charging mount for self-regulated recharging and a Battery Management System (BMS) for safe operation.

## 🛠️ Hardware Specifications
* **Main Controller:** Raspberry Pi 4B (running Ubuntu)
* **Auxiliary Controller:** Arduino Uno R3 (for low-level motor and sensor processing)
* **Sensors:** * LDROBOT LD06 LiDAR
    * Ultrasonic HC-SR04 Sensors
    * Infrared (IR) Sensors
* **Drive System:** * JGB37-520 DC Gear Motors
    * Dual BTS7960 High-Power Motor Drivers
* **Power System:** * 12V 12000mAh Lithium-ion battery
    * 3S BMS (Battery Management System)
    * LM2596S Buck Converters
* **Cleaning Mechanism:** * High-speed BLDC vacuum motor
    * Dual GA12-N20 side brushes

## 💻 Software Stack
* **Operating Systems:** Ubuntu Linux (RPi), Windows 10/11 (Development)
* **Programming Languages:** Python (Core Logic), C++ (Arduino Firmware)
* **Development Tools:** Arduino IDE, Flutter SDK (Mobile App), VS Code
* **Communication:** 2.4 GHz Wi-Fi Protocol for App-to-Robot interaction

## 📊 Performance Evaluation
In formal field testing, Roomi achieved a **Grand Weighted Mean of 4.50**, interpreted as **"Strongly Agree"** across ISO/IEC 25010 quality standards:

| Criteria | Score | Interpretation |
| :--- | :--- | :--- |
| **Usability** | 4.62 | Strongly Agree |
| **Reliability** | 4.57 | Strongly Agree |
| **Performance Efficiency** | 4.49 | Agree |
| **Functionality** | 4.44 | Agree |
| **Portability & Design** | 4.37 | Agree |

## 👥 The Team
* **Seno, Naj Allen R.**
* **Huila, Renzo**
* **Tondo, Joshapat Ai M.**
* **Valenzuela, Kyle Andrei L.**

---
© 2026 Southern Philippines Institute of Science & Technology - Bachelor of Science in Computer Engineering

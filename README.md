# 🏥 AUTOMED - Autonomous Medical Delivery Robot

AUTOMED is an **autonomous indoor medical delivery robot** designed to improve operational efficiency in healthcare environments such as **hospitals, clinics, and pharmacies**. Built with advanced SLAM-based navigation, real-time obstacle avoidance, and secure payload handling, AUTOMED ensures **efficient, contactless, and secure delivery** of medical supplies.

---

## 🚀 Project Overview

AUTOMED integrates **SLAM (Simultaneous Localization and Mapping)** using LiDAR and IMU, **A\\*** algorithm for path planning, and **sensor fusion via an Extended Kalman Filter (EKF)** to autonomously navigate and deliver within dynamic hospital environments. A **Flutter-based mobile application** allows intuitive control, manual override, real-time notifications, and secure user authentication.

---

## ✨ Features

- 🤖 Fully autonomous navigation using SLAM and A* algorithm  
- 🧠 Sensor fusion with EKF for robust obstacle avoidance  
- 📷 Visual feedback and remote monitoring with onboard camera  
- 🔐 RFID-based payload access security  
- 📱 Mobile app with real-time control, status, and notifications  
- 🛠 Dual-processor architecture: Raspberry Pi 4B + Arduino Uno  

---

## 🧠 Tech Stack

### Hardware
- Raspberry Pi 4B (ROS2 Processing)
- Arduino Uno (Motor & RFID Control)
- RPLidar A1M8 (2D Mapping)
- BNO085 IMU
- Ultrasonic Sensors
- USB Camera
- Rack & Pinion Mechanism (Tray)
- RFID Reader
- DC Gear Motors with Relay Modules
- 12V Battery Pack + Buck Converters
- Aluminum Chassis & Acrylic Enclosure

### Software
- ROS2 (Robot Operating System)
- Python (ROS Nodes)
- C/C++ (Arduino Control)
- Flutter (Mobile Application)
- Firebase (Authentication & Feedback)
- A* Pathfinding Algorithm
- EKF Sensor Fusion
- SLAM (Localization & Mapping)
---

## 🧰 Hardware Components

| Component               | Description                                 |
|------------------------|---------------------------------------------|
| Raspberry Pi 4B        | Primary processing unit (ROS2)              |
| Arduino Uno            | Secondary processor for motors/RFID         |
| RPLidar A1M8           | 2D Mapping & Obstacle Detection             |
| BNO085 IMU             | Orientation and stability tracking          |
| Ultrasonic Sensors     | Close-range obstacle detection              |
| USB Camera             | Live video feed for monitoring              |
| RFID Module            | Secure payload access                       |
| DC Gear Motors         | Mobility and tray extension                 |
| 12V Battery Pack       | Main power source                           |
| Buck Converters        | Voltage regulation                          |
| Aluminum Chassis       | Lightweight and strong structure            |

---

## 🛠️ Setup & Installation

1. **Assemble** the robot hardware using the aluminum and acrylic chassis.
2. **Upload** ROS2-based code on Raspberry Pi and Arduino firmware via Arduino IDE.
3. **Install** the Flutter mobile app on an Android device.
4. **Connect** Raspberry Pi and mobile device to the hospital’s Wi-Fi.
5. **Authenticate** using Firebase to gain access to robot control features.
6. **Scan the map** using SLAM and assign destinations using the app.

---

## ✅ Testing

- **Simulations**: Conducted using RViz & Gazebo.
- **Navigation**: Verified with SLAM + A* across dynamic hospital scenarios.
- **Obstacle Avoidance**: Real-time tested with static and moving objects.
- **Payload Delivery**: RFID authentication ensures secure handoff.
- **App Functionality**: Tested real-time control, feedback, and notifications.

---

## 🚧 Future Enhancements

- 🤖 Integration with HIS/EHR systems for real-time hospital workflow sync  
- 🧬 AI-based object/person detection with YOLO & U-Net  
- 🔊 Voice and facial recognition for enhanced security  
- 📡 Multi-robot collaboration for large-scale hospital deployments  
- 🌐 Cloud-based analytics and monitoring dashboard  

---

## 👨‍💻 Team

- **Shawn Sam Varghese** (MGP21UCS135)  
- **Kevin Kizhakekuttu Thomas** (MGP21UCS089)  
- **Sreejith A** (MGP21UCS137)  
- **Midhun Sreenivas** (MGP21UCS105)

**Project Guide**: Er. Gayathri J L  
**Institution**: Saintgits College of Engineering (Autonomous)  
**University**: APJ Abdul Kalam Technological University  
**Year**: 2024–2025

---

## 📄 License

This project was developed for academic and research purposes. For commercial use or further development, please contact the project authors or the academic supervisor.
"""


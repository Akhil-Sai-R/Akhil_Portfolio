---
title: "Autonomous Driving Prototype Using Embedded Systems and AI"
description: "Bringing autonomous vehicles to life with AI-driven prototypes."
draft: false
tags: ["Autonomous Vehicles", "AI", "Machine Learning", "Deep Learning", "Raspberry Pi", "Embedded Systems"]
showToc: false
weight: 215
cover:
    image: "projects/autonomus_vehicle/AIV_self_main.jpg"
--- 
## Description

This project showcases the development of an **Autonomous Vehicle System (AVS) prototype**, integrating advanced **AI, Machine Learning (ML), and Deep Learning (DL)** techniques with embedded systems. The project leverages a combination of **Raspberry Pi 4**, **Arduino**, and **NVIDIA Jetson Nano/TX2 NX**, along with additional hardware components, to create a scalable and efficient system that simulates real-world autonomous vehicle capabilities.

### **Key Features:**
- **Self-driving:** Autonomous navigation with path following.
- **Obstacle avoidance:** Detection and navigation around obstacles using ultrasonic sensors and LiDAR/Radar.
- **Self-parking:** Automated parking into predefined spaces.
- **Traffic signboard recognition:** Classification of traffic signs using machine learning models.
- **Voice command recognition:** Hands-free vehicle control through voice inputs.
- **Waypoint navigation:** GPS-based precise navigation to specific destinations.
- **Real-time data collection:** Integration of telemetry and sensor data for system optimization.

### **Hardware Components:**
- **Primary Hardware:**
  - Raspberry Pi 4
  - Arduino
  - Raspberry Pi Camera with Night Vision Sensors
  - L298D Motor Drive
  - Raspberry Pi Microphone and Speaker
- **Additional Hardware:**
  - Ultrasonic Sensors
  - LiDAR/Radar
  - GPS Module
  - Bluetooth Module

### **Concepts and Technologies:**
- **Computer Vision:** Object detection, sign recognition, and real-time image processing using **OpenCV**.
- **Machine Learning and Deep Learning:** TensorFlow and PyTorch-based models for sign classification and voice recognition.
- **GPS Navigation:** Waypoint-based navigation for precise route planning.
- **Obstacle Avoidance:** Real-time distance measurement and navigation using ultrasonic sensors and LiDAR.
- **Auto Parking:** Automated parking algorithms for efficient maneuvering.
- **Traffic Signboard Recognition:** AI-driven recognition of traffic signs to simulate real-world scenarios.

### **Programming Languages:**
- **Python:** (80%) Used for most AI, ML, and sensor data processing tasks.
- **C++:** (20%) For low-level hardware integration and control.
- **Java and CSS:** For GPS tracking through mobile and smartwatch applications

### **Working Process:**
1. **Data Input:** Real-time data collection from ultrasonic sensors, LiDAR, and cameras.
2. **Data Processing:** 
   - Object detection and obstacle avoidance using OpenCV and machine learning models.
   - Traffic sign recognition and decision-making with TensorFlow 2.0.
3. **Vehicle Control:** Autonomous navigation and parking using processed sensor data.
4. **Output and Monitoring:** Real-time visualization and monitoring via a local server (localhost).

### **Applications:**
- Autonomous driving research and development.
- Robotics and intelligent automation.
- Smart transportation systems.
- AI-based real-time monitoring and data collection.

The **Autonomous Driving Prototype** combines cutting-edge AI techniques with practical embedded systems to offer a versatile and scalable solution for autonomous navigation and control. This project demonstrates how emerging technologies can be used to bridge the gap between AI research and real-world applications.
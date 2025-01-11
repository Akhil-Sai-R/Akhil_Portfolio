---
title: "Autonomous Driving Rover: Project MOWME"
description: "Building a smart, autonomous rover capable of learning, navigation, and environmental analysis."
draft: false
tags: ["Autonomous Vehicles", "AI", "Machine Learning", "Deep Learning", "IoT", "AWS"]
showToc: false
weight: 209
cover:
    image: "projects/mowme/Mowme.png"
--- 
## Description

Project **MOWME** is an innovative **Autonomous Driving Rover** prototype designed to showcase advanced AI, ML, and IoT-driven capabilities. The rover is built to autonomously navigate, classify objects, collect and self-train data, and transfer insights to the cloud for future learning. This system integrates advanced hardware with cloud storage and machine learning for real-time decision-making and environmental analysis.

### **Key Features**
1. **Object Classification:** The rover uses machine learning to identify and classify objects in its environment.
2. **Auto-Data Collection:** Captures real-time sensor and camera data, processing it locally or storing it in the cloud.
3. **Self-Training:** Implements feedback loops to refine object classification and navigation algorithms over time.
4. **Auto-Navigation:** Incorporates **GPS waypoint navigation** for autonomous movement across dynamic terrains.
5. **Obstacle Avoidance:** Uses ultrasonic sensors for collision detection and avoidance.
6. **Cloud Integration:** Data is stored on **AWS Cloud**, enabling future training and analysis.
7. **Environmental Monitoring:** Detects diseases in grass using **Convolutional Neural Networks (CNN)**, identifying patterns like dryness or overwatering.

### **Hardware Components**
- **Core Components:**
  - Raspberry Pi 4
  - Arduino
  - Raspberry Pi Camera
  - L298D Motor Drive
- **Additional Sensors:**
  - Ultrasonic Sensors
  - GPS Module
  - Bluetooth Module

### **Software Features**
1. **Wireless Drive Control:** The rover can be controlled using MQTT protocol for wireless operation.
2. **Video Streaming:** Real-time video streaming from Raspberry Pi to a laptop for monitoring.
3. **Dataset Collection:** Automatically captures and processes images for model training, storing them locally or in the cloud.
4. **Disease Detection in Grass:** Leverages CNN models to analyze grass conditions and classify diseases.

### **Working Process**
1. **Data Collection:**
   - Captures sensor data, camera images, and ultrasonic measurements.
   - Transfers data to AWS Cloud for processing and storage.
2. **Data Processing:**
   - Object classification and dataset analysis using **TensorFlow** and **CNN models**.
   - Disease detection in grass based on visual patterns.
3. **Navigation and Control:**
   - Utilizes GPS and sensor data for waypoint navigation.
   - Avoids obstacles dynamically with ultrasonic sensors.
4. **Wireless Communication:**
   - MQTT protocol enables seamless communication between devices.
   - Live monitoring of rover operations via Raspberry Pi.

### **Programming Languages**
- **Python:** (80%) Core logic, machine learning models, and data processing.
- **C++:** (20%) For low-level hardware interaction and control.
- **AWS Integration:** IoT and cloud-based storage for scalability.

### **Applications**
- Autonomous lawn management systems.
- Environmental monitoring and data collection.
- IoT-driven robotics for agriculture.
- AI-based disease detection and analytics.

The **MOWME Rover** demonstrates the seamless integration of hardware, AI, and cloud services, offering a versatile solution for autonomous systems and environmental analysis. This project is a step forward in creating smart, scalable, and adaptive IoT-enabled devices for practical use cases.

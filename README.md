# 🚀 Obstacle Detection and Tracking System

## 📌 Overview
This project is an Arduino-based system that detects obstacles using an ultrasonic sensor and tracks them using a servo motor. It provides visual and sound alerts using LEDs and a buzzer.

---

## 🛠️ Components Used
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Servo Motor (SG90)
- Buzzer
- LEDs
- Breadboard & Jumper Wires

---

## ⚙️ Working
- Ultrasonic sensor measures distance
- Servo rotates to scan surroundings
- If obstacle detected:
  - Red LED ON
  - Buzzer ON
- Otherwise:
  - Green LED ON

---

## 🔌 Connections
- TRIG → Pin 9  
- ECHO → Pin 10  
- Servo → Pin 6  
- Green LED → Pin 2  
- Red LED → Pin 3  
- Buzzer → Pin 4  

---

## 🖼️ Circuit Diagram
![Circuit](images/circuit.png)

---

## 📷 Project Setup
![Setup](images/setup.jpg)

---

## 🎥 Working Demo
👉 [Watch Video](https://drive.google.com/file/d/1LLrxssoqVm3YYxh3ZLr4v7bT5ghL2Jck/view?usp=drive_link)

---

## 💻 Code
Available in:
`code/Obstacle_Tracking_System.ino`

---

## 🚀 Future Improvements
- Add IoT (send alert to mobile)
- Add camera for AI detection
- Improve accuracy using filters

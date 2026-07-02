# 🚗 DRIVE CLEAN: Technology for Tracking Vehicle Emission

## 📖 Overview
Drive Clean is an IoT-based vehicle emission monitoring system developed to modernize the conventional Pollution Under Control (PUC) testing process. The system continuously monitors vehicle exhaust emissions using multiple gas sensors, displays real-time readings on a TFT touch display, and transmits the collected data to a Django-based web server for processing, storage, and digital certificate generation. Vehicle owners can securely retrieve and download their emission certificates through a web portal. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

---

## ✨ Key Features

- Real-time vehicle emission monitoring
- Carbon Monoxide (CO), Hydrocarbon (HC), and Air Quality detection
- GPS-based vehicle location tracking
- TFT Touch Display interface
- ESP32-based IoT system
- Django-powered web application
- Automatic PASS/FAIL evaluation
- Digital PUC certificate generation
- Online certificate download portal
- Secure database for emission records

---

## 🛠 Hardware Components

- ESP32 Development Board
- MQ-2 Gas Sensor
- MQ-7 Carbon Monoxide Sensor
- MQ-135 Air Quality Sensor
- NEO-6M GPS Module
- 3.5" TFT Touch Display (ILI9341)
- LM2596 Buck Converter
- 12V Battery
- Capacitors
- Jumper Wires

---

## 💻 Software Used

- Arduino IDE
- Python
- Django
- Django REST Framework
- SQLite
- HTML
- CSS
- JavaScript
- Git & GitHub

---

## 🧑‍💻 Programming Languages

- Python
- C++
- HTML
- CSS
- JavaScript
- SQL

---

## ⚙️ System Workflow

1. Vehicle exhaust gases are detected using MQ-series sensors.
2. ESP32 processes the sensor data.
3. GPS captures the vehicle location.
4. Live readings are displayed on the TFT Touch Display.
5. Data is transmitted to the Django web server over Wi-Fi.
6. The server validates emission levels.
7. A digital PUC certificate is generated.
8. Users can retrieve and download their certificate through the web portal. :contentReference[oaicite:2]{index=2}

---

## 📂 Project Structure

```
DRIVE-CLEAN
│
├── Django_Server/
├── ESP32_Code/
├── Images/
├── Documentation/
├── Videos/
├── README.md
└── requirements.txt
```

---

## 📸 Project Images

*(Upload your project photos inside the Images folder.)*

---

## 🎥 Demo Video

Add your Google Drive or YouTube link here.

Example:

https://drive.google.com/your-demo-video-link

---

## 📄 Project Report

Upload your project report inside the Documentation folder or provide the link here.

---

## 👨‍💻 Developed By

Abinesh K

Electronics and Communication Engineering

K.L.N College of Engineering

---

## 📜 License

This project is developed for academic and research purposes.

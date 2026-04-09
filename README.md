# jules-ffjnashfgahbsdvhjrepovcvzfdfdafafvzv
Repository for Jules AI task


flowchart TD

A[IR Sensors<br>IR1 IR2 IR3 IR4] --> B[ESP32 Controller]

B --> C[Servo Motor<br>Gate Control]
B --> D[LED Indicators<br>Green/Red per Slot]
B --> E[WiFi Module<br>ESP32 Built-in]

E --> F[Web Server (Port 80)]
F --> G[Browser UI<br>System Monitor Dashboard]


# 🚗 Smart Parking System (ESP32 + Web Dashboard)

This project uses an ESP32 with IR sensors, LEDs, and a servo motor to create a smart parking system with a live web dashboard.

---

## 📊 System Architecture

```mermaid
flowchart TD

A[IR Sensors<br>IR1 IR2 IR3 IR4] --> B[ESP32 Controller]

B --> C[Servo Motor<br>Gate Control]
B --> D[LED Indicators<br>Green/Red per Slot]
B --> E[WiFi Module<br>ESP32 Built-in]

E --> F[Web Server (Port 80)]
F --> G[Browser UI<br>System Monitor Dashboard]
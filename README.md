# Stored-Grain-Protection-Spoilage-Alert-System
The main objective of this project is to reduce grain spoilage and improve storage safety by providing a real-time monitoring and alert system that helps farmers take immediate action when environmental conditions become unsafe.

---Project Overview---

The Smart Grain Protection & Spoilage Alert System is an IoT-based solution designed to monitor grain storage conditions such as temperature and humidity in real time. The system helps prevent grain spoilage by alerting users when environmental conditions become unsafe.
The project uses an ESP32 microcontroller, DHT22 sensor, and the Blynk IoT platform to monitor and notify users through a mobile application.

---Objectives---
Monitor grain storage conditions in real time
Detect temperature and humidity changes in storage areas
Alert users when environmental values exceed safe limits
Send notifications through the Blynk mobile application
Provide a low-cost and energy-efficient monitoring system

 ---Problem Statement

Grains stored in warehouses or storage units are vulnerable to high temperature, humidity, and harmful gases. These conditions can lead to fungus growth, insect infestation, and grain spoilage, causing economic losses.

Manual monitoring is inefficient, so an automated monitoring and alert system is required.

💡 Proposed Solution

This project proposes a simple and cost-effective IoT-based monitoring system using:

ESP32 microcontroller

DHT22 temperature and humidity sensor

Blynk mobile application

Local alert system (buzzer / LED)

When abnormal conditions are detected, the system sends instant alerts to the user and activates a local buzzer alarm.

⚙️ System Components
Component	Description
ESP32	Main microcontroller for data processing and IoT communication
DHT22 Sensor	Measures temperature and humidity
Buzzer / LED	Provides local alerts when unsafe conditions occur
WiFi (ESP32 built-in)	Sends data to cloud server
Blynk App	Displays sensor data and sends notifications
Solar Panel (Optional)	Provides eco-friendly power supply
🔄 Working Principle

The ESP32 microcontroller collects data from the DHT22 sensor.

Temperature and humidity values are compared with predefined safe limits.

If the values exceed the threshold:

A buzzer or LED alert is triggered.

A notification is sent to the Blynk mobile app.

The system continuously monitors the environment and updates data in real time.

📊 Block Diagram

Sensor (DHT22) → ESP32 Microcontroller → Buzzer / LED Alert
↓
Blynk Cloud
↓
Mobile Notification

🧪 Technical Approach

Data Collection
The DHT22 sensor measures temperature and humidity inside the grain storage environment.

Data Processing
ESP32 reads sensor data and compares it with safe threshold values.

Alert System
If values exceed safe limits:

Buzzer alerts locally

Notification sent through Blynk app

Power Supply
The system can operate using solar power for eco-friendly operation.

✅ Advantages

Real-time monitoring of grain storage conditions

Automatic alerts and notifications

Prevents grain spoilage and financial loss

Low-cost and easy to implement

Energy-efficient with solar power support

Minimal manual monitoring required

📍 Applications

Grain warehouses

Agricultural storage facilities

Food grain storage systems

Smart farming solutions

🔮 Future Improvements

Add gas sensors for detecting harmful gases

Integrate machine learning for predictive spoilage detection

Develop a web dashboard for remote monitoring

Add SMS alerts for areas without internet access

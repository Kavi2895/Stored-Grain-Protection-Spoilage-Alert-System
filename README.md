# Stored-Grain-Protection-Spoilage-Alert-System
The main objective of this project is to reduce grain spoilage and improve storage safety by providing a real-time monitoring and alert system that helps farmers take immediate action when environmental conditions become unsafe.

---PROJECT DESCRIPTION---

The Smart Grain Protection & Spoilage Alert System is an IoT-based solution designed to monitor grain storage conditions such as temperature and humidity in real time. The system helps prevent grain spoilage by alerting users when environmental conditions become unsafe.
The project uses an ESP32 microcontroller, DHT22 sensor, and the Blynk IoT platform to monitor and notify users through a mobile application.

---OBJECTIVES---
* Monitor grain storage conditions in real time
* Detect temperature and humidity changes in storage areas
* Alert users when environmental values exceed safe limits
* Send notifications through the Blynk mobile application
* Provide a low-cost and energy-efficient monitoring system

 ---PROBLEM STATEMENT---

Grains stored in warehouses or storage units are vulnerable to high temperature, humidity, and harmful gases. These conditions can lead to fungus growth, insect infestation, and grain spoilage, causing economic losses.
Manual monitoring is inefficient, so an automated monitoring and alert system is required.

--- PROPOSED SOLUTION---

1)This project proposes a simple and cost-effective IoT-based monitoring system using:
2)ESP32 microcontroller
3)DHT22 temperature and humidity sensor
4)Blynk mobile application
5)Local alert system (buzzer / LED)
6)When abnormal conditions are detected, the system sends instant alerts to the user and activates a local buzzer alarm.

---SYSTEM COMPONENT--

1)Component	Description
2)ESP32	Main microcontroller for data processing and IoT communication
3)DHT22 Sensor	Measures temperature and humidity
4)Buzzer / LED	Provides local alerts when unsafe conditions occur
5)WiFi (ESP32 built-in)	Sends data to cloud server
6)Blynk App	Displays sensor data and sends notifications
7) Solar Panel (Optional)	Provides eco-friendly power supply

---WORKING PRINCIPLE---

* The ESP32 microcontroller collects data from the DHT22 sensor.
* Temperature and humidity values are compared with predefined safe limits.
* If the values exceed the threshold:
* A buzzer or LED alert is triggered.
* A notification is sent to the Blynk mobile app.
* The system continuously monitors the environment and updates data in real time.


---ADVANTAGES---

1)Real-time monitoring of grain storage conditions
2)Automatic alerts and notifications
3)Prevents grain spoilage and financial loss
4)Low-cost and easy to implement
5)Energy-efficient with solar power support
6)Minimal manual monitoring required

---APPLICATIONS---

* Grain warehouses
* Agricultural storage facilities
* Food grain storage systems
* Smart farming solutions

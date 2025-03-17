# 🌦️ IoT-Based Weather Monitoring System using ESP32  

This project is an **IoT-based weather monitoring system** that uses an **ESP32 microcontroller** to collect real-time weather data, display it on an LCD, and send it to the **IoT Gecko cloud platform** for remote monitoring.  

## 📌 Features  
- **Real-time Weather Data Collection** using **DHT11 (Temperature & Humidity)** and **Rain Sensor**.  
- **Local Monitoring** via **16x2 I2C LCD Display**.  
- **Remote Monitoring** via **IoT Gecko Cloud Platform**.  
- **WiFi-enabled** for cloud data transmission.  

## 🛠️ Components Used  
- **ESP32** (WiFi-enabled microcontroller)  
- **DHT11 Sensor** (Temperature & Humidity)  
- **Rain Sensor** (Detects rainfall)  
- **16x2 LCD (I2C)** (Displays local weather data)  
- **IoT Gecko Cloud Platform** (Stores and displays real-time data online)  

## 🔗 Circuit Connections  
| Component | ESP32 Pin |  
|-----------|----------|  
| DHT11 (VCC) | 3.3V |  
| DHT11 (GND) | GND |  
| DHT11 (Data) | GPIO4 |  
| Rain Sensor (VCC) | 3.3V |  
| Rain Sensor (GND) | GND |  
| Rain Sensor (Digital Output) | GPIO5 |  
| LCD (SDA) | GPIO21 |  
| LCD (SCL) | GPIO22 |  

## 🚀 How to Use  
1. **Install Required Libraries** in Arduino IDE:  
   - `DHT sensor library` (by Adafruit)  
   - `Adafruit Unified Sensor`  
   - `LiquidCrystal_I2C`  
   - `WiFi` and `HTTPClient` (built-in)  

2. **Clone this Repository**  
   ```sh
   git clone https://github.com/your-username/ESP32-Weather-Monitoring.git
   cd ESP32-Weather-Monitoring

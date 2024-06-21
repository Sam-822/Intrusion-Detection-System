
# Intrusion Detection System

### Overview
This project uses an ESP32-CAM module to create a Telegram bot that can capture and send photos. The bot can be controlled via Telegram commands and can also automatically take and send photos when motion is detected using a PIR sensor. The project uses the ESP32-CAM library, WiFi, and UniversalTelegramBot libraries to achieve this functionality.

## Hardware Required
- ESP32-CAM Module
- PIR Sensor
- Flash LED (optional, connected to GPIO 4)
- Power supply for ESP32-CAM (usually 5V)

## Libraries Used
- `Arduino.h`
- `WiFi.h`
- `WiFiClientSecure.h`
- `esp_camera.h`
- `UniversalTelegramBot.h`
- `ArduinoJson.h`

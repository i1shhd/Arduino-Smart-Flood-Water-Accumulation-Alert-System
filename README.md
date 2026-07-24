# Arduino Smart Flood & Water Accumulation Alert System

An Arduino-based IoT system designed to monitor water levels and provide real-time flood alerts. The system continuously measures the distance between the sensor and the water surface using an ultrasonic sensor. When the water level reaches predefined thresholds, visual indicators and Bluetooth notifications are activated to provide early warnings.



![Project Preview](Project_Image.jpg)


## Features

- Real-time water level monitoring
- Flood and water accumulation detection
- Bluetooth-based alert notifications
- LCD display for live water level status
- LED indicators for safe, warning, and danger levels
- Arduino Uno implementation

## Hardware

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Bluetooth Module
- 16×2 LCD Display
- LEDs
- Jumper Wires

## Software

- Arduino IDE
- C++

## Project Structure

```
Arduino-Smart-Flood-Water-Accumulation-Alert-System/
│
├── Arduino_Code.ino
└── README.md
```

## How It Works

1. The ultrasonic sensor measures the water level.
2. Arduino processes the measured distance.
3. The current status is displayed on the LCD.
4. LEDs indicate the water level condition.
5. Bluetooth sends an alert when the danger threshold is reached.

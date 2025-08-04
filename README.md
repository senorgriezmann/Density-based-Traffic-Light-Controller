# Density-based Traffic Light Controller 🚦

A smart traffic light simulation that adjusts signal timing based on real-time traffic density using Arduino and Python.

## 🔧 Tech Stack
- Python (Serial communication)
- Arduino UNO (C++)
- IR Sensors (for vehicle detection)
- LEDs (to simulate traffic lights)

## 🧠 How It Works
- IR sensors detect vehicle presence in each lane.
- Arduino reads sensor inputs and sends traffic density data over serial.
- Python script receives data and adjusts light duration accordingly.
- Mimics a real-world, adaptive traffic light system.

## 🛠️ Setup Instructions

### Arduino
1. Upload `arduino.ino` to your Arduino UNO using Arduino IDE.
2. Connect IR sensors and LEDs according to the diagram below.

### Python
1. Install dependencies:

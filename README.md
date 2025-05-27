 🚧 Pothole Detection & Alert System

An Arduino-based project that detects potholes using IR and ultrasonic sensors, activates alerts (LED, buzzer), and sends SMS notifications via GSM to multiple phone numbers.

 🛠️ Features

* **IR Sensor**: Detects nearby movement (e.g., vehicle presence)
* **Ultrasonic Sensor**: Measures distance to detect potholes
* **Servo Motor**: Simulates barrier movement
* **Buzzer & LED**: Audio-visual alert
* **GSM Module (SIM800L)**: Sends SMS alerts to predefined contacts

 📲 SMS Alert Example

> ⚠ Warning: Object detected near a pothole! 🚨

 📦 Components

* Arduino UNO
* IR Sensor
* Ultrasonic Sensor (HC-SR04)
* Servo Motor
* Buzzer & LED
* SIM800L GSM Module
* Jumper wires, Breadboard, etc.

 🔧 How It Works

1. **IR Sensor** triggers the servo movement when an object is detected.
2. **Ultrasonic Sensor** checks distance. If < 10 cm:

   * Buzzer and LED turn ON.
   * SMS is sent to multiple phone numbers.

 ⚙️ Pin Configuration

* IR Sensor: Pin 2
* Servo: Pin 5
* Ultrasonic: Trig 6, Echo 7
* Buzzer: Pin 8
* LED: Pin 9
* GSM: TX 10, RX 11



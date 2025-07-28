# 🛸 Arduino Sonar Scanner

This Arduino project is coded in **C++**, is a **sonar scanner** that uses a **servo motor** and an **ultrasonic sensor (HC-SR04)** to detect objects, measure distances across an arc, and display the scanned object as a **red dot** on a radar-style screen using Processing.

## 🔧 How It Works

- The **servo motor** rotates from 0° to 180°, scanning the area in front of it.
- At each angle, the **ultrasonic sensor** measures the **distance** to the nearest object.
- The measured distance is:
  - Sent to the **Serial Monitor**, and
  - Visualized as a **red dot** on a radar-style display using Processing.

This simulates how real sonar systems scan an area to detect obstacles.

## 🧰 Hardware Used

- Arduino Uno (or compatible board)
- SG90 Servo Motor
- HC-SR04 Ultrasonic Sensor
- Breadboard or sensor mount
- Jumper wires
- USB cable for programming

## 🖥️ Software Requirements

- [Arduino IDE](https://www.arduino.cc/en/software)
- [Processing IDE](https://processing.org/download/) *(for radar display)*

## 💡 Notes

- Make sure the **HC-SR04** sensor is securely mounted and aligned straight.
- You can customize the servo range and scanning speed in the code.
- The Processing sketch reads serial data and plots dots based on angle and distance.

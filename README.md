# Ultrasonic-Distance-Based-LED-Alert-System
This project uses an HC-SR04 ultrasonic sensor to measure distance and lights up the built-in LED when an object is detected within 100 cm. It’s a simple IoT system ideal for learning sensor-based control, with real-time distance data displayed via Serial Monitor. Perfect for beginners in Arduino and automation.

## 📌 Project Description

This IoT project uses an **ultrasonic sensor (HC-SR04)** to measure the distance to an object and activates the **onboard LED** when the object is detected within **100 centimeters**. It’s a simple yet effective demonstration of using sensor data to trigger real-world actions—perfect for learning how to integrate hardware components with microcontroller logic.

## ⚙️ How It Works

- The **TRIG pin** sends a short ultrasonic pulse.
- The **ECHO pin** listens for the reflected pulse to calculate the time it takes to bounce back.
- The time is converted into **distance in centimeters** using the speed of sound.
- If an object is **closer than 100 cm**, the **built-in LED lights up**.
- The **distance is printed via Serial** at 115200 baud for monitoring.

## 🔗 Try it on Wokwi

You can simulate and test this project online using Wokwi:

👉 [**Open Wokwi Simulation**](https://wokwi.com/projects/428046376770365441)

_(Replace the placeholder above with your actual Wokwi project URL.)_

## 💡 Use Cases

- Proximity-based alerts  
- Smart parking assistants  
- DIY home automation  
- Obstacle detection in robotics

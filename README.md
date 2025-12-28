**🚪 Automated Door System using Arduino Uno**
📌 Project Overview

The Automated Door System is a beginner-friendly embedded systems project that demonstrates the principles of automation using sensors and actuators. This system uses an IR sensor to detect human motion and automatically controls servo motors to simulate the opening and closing of a door. An LED indicator provides visual feedback when the door is open.

This project is designed and simulated using Wokwi, making it easy to understand, test, and demonstrate without physical hardware.

**🎯 Objectives**

Understand how sensors detect real-world inputs

Learn how actuators (servo motors) respond to control signals

Implement basic automation logic using Arduino

Gain hands-on experience with embedded systems programming

**🛠️ Components Used**

Arduino Uno

IR Sensor

Servo Motor(s)

LED

220Ω Resistor

Jumper Wires

Breadboard

Arduino IDE / Wokwi Simulator

**⚙️ Working Principle**

The IR sensor continuously monitors for the presence of a human.

When motion is detected, the sensor sends a digital signal to the Arduino.

The Arduino processes this input and:

Activates the servo motor to open the door

Turns ON the LED to indicate the door is open

When no motion is detected:

The servo motor returns to its initial position, closing the door

The LED turns OFF

A fixed delay ensures smooth operation and avoids rapid door movement.

**🔌 Circuit Description**

The IR sensor output is connected to a digital input pin on the Arduino.

The servo motor signal pins are connected to PWM-capable digital pins.

The LED is connected through a current-limiting resistor.

All components share a common ground.

**💻 Software Implementation**

Written in Embedded C using Arduino framework

Uses the Servo.h library for motor control

Digital input is used to read IR sensor output

Conditional logic determines door open and close states

**▶️ Simulation & Testing**

The project is simulated using Wokwi

IR sensor detection is manually triggered during simulation

Servo rotation and LED behavior are observed to verify functionality

**📸 Output**

Door opens automatically when motion is detected

LED turns ON as an indicator

Door closes automatically when no motion is present

**🚀 Applications**

Automatic sliding doors

Smart home automation

Entry systems in malls, offices, and hospitals

Touchless access control systems

**📚 Learning Outcomes**

Basics of Arduino programming

Understanding IR sensors and servo motors

Hands-on experience with automation systems

Practical knowledge of embedded systems concepts

**🧩 Future Enhancements**

Add a buzzer for audio indication

Implement dual servo doors for realistic operation

Integrate LCD display for status messages

Use PIR sensor for improved motion detection

Implement IoT connectivity for remote monitoring

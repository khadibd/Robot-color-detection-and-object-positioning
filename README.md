Arduino Robotics Control System

This project utilizes an Arduino microcontroller to control two DC motors and RGB LEDs based on environmental inputs and predefined commands. The system integrates motor control for movement and obstacle avoidance, along with LED feedback for status indication.

Functionality Overview:
1. Motor Control:

Forward Movement: Moves both motors (Motor A and Motor B) forward with adjustable speed using Pulse Width Modulation (PWM).
Turning:
Left Turn: Turns left by controlling the motors accordingly.
Right Turn: Turns right by adjusting motor directions and speeds.
Stop Function: Halts all motor operations instantly.
2. LED Feedback:

Status Indicators: Utilizes RGB LEDs to provide visual feedback.
Green LED: Indicates forward movement and operation readiness.
Red LED: Reserved for future use (currently commented out).
Blue LED: Activates briefly during specific actions.
3. Control Logic:

Loop Function: Executes a sequence of predefined actions in a loop.
Obstacle Detection: Pauses movement upon detecting obstacles, indicated by a temporary LED activation.
Setup and Components:
Hardware: Requires Arduino board, two DC motors with corresponding motor drivers, and RGB LEDs.
Software: Developed using Arduino IDE with integration of PWM for motor speed control and digital outputs for LED control.
Future Enhancements:
Sensor Integration: Planned addition of sensors (e.g., ultrasonic or IR sensors) for autonomous obstacle detection and navigation.
Expanded Functionality: Potential expansion to include pathfinding algorithms or remote control capabilities via Bluetooth or Wi-Fi.
This project serves as a foundational framework for developing autonomous or semi-autonomous robotic systems, ideal for educational purposes or as a starting point for more complex robotics applications.

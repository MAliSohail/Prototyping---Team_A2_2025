# Line-Following and Obstacle-Detection Robot
This repository contains the code, design files, and documentation for an Arduino-based line-following robot with autonomous navigation and obstacle detection capabilities.
The robot uses infrared (IR) sensors for line tracking, ultrasonic for obstacle detection and a color sensor for identifying obstacle color. Its chassis is designed in CAD to ensure optimal sensor placement and efficient movement.

## Project Overview
This robot is engineered to autonomously navigate a marked path by following a line detected by IR sensors.
A color sensor enables it to identify and avoid obstacles based on color differentiation, dynamically adjusting its route.
This project demonstrates the integration of multiple sensors and control systems to achieve real-time navigation and obstacle avoidance.

## Key Features
CAD-Designed Holders
Carefully designed in CAD software for structural stability and optimal placement of sensors and motors.

### Line Tracking
IR sensors detect a dark line on a lighter surface, guiding the robot along a predefined path.

### Color-Based Obstacle Detection
The color sensor identifies obstacles by analyzing color, allowing the robot to steer clear of obstructions.

### Motor Control
An L298 motor driver processes Arduino commands to precisely control motor speed and direction.

## Team Collaboration
This project was a collective effort, with all team members actively contributing to design, coding, and testing.
Hardware and software decisions were made collaboratively, with each component reviewed to maintain a high standard of quality and functionality.

## Hardware Components
Arduino: Processes sensor inputs and sends motor control signals.

### IR Sensors: 
Used for line detection and path following.

### Color Sensor: 
Identifies obstacles by their color.

### Ultrasonic Sensor: 
Adds distance-based obstacle detection capability.

### L298 Motor Driver: 
Controls the motors based on Arduino commands.

## Setup and Usage

### Assembly
Build the CAD-designed holders for IR sensors, breadboard and battery, ultrasonic sensor, and motors.

Mount the IR sensors, color sensor, and motor driver connected to the Arduino.

### Upload Code
Flash the provided program to the Arduino using the Arduino IDE.

### Testing
Place the robot on a track and observe its line-following and obstacle-avoidance behaviors.

## Future Improvements

### Refine Motor Control
Improve control logic for smoother, slower, and more precise line-following to navigate curves and stay on track.

### Implement Adaptive Learning
Explore machine learning or adaptive control techniques for smarter path optimization and dynamic adjustment to track variations.

## Observations & Challenges
### Motors
The motors operated at a minimum speed that was still too high, causing frequent overshooting and veering off the line, which reduced tracking precision.

### Ultrasonic Sensor
Failed to detect obstacles during tests, possibly due to placement, wiring, or configuration issues.

### Color Sensor
Was not properly calibrated within the project timeline, and therefore did not function as intended for obstacle detection.

### IR Sensors
Successfully detected and followed the line, but the robot's high speed due to motor limitations compromised stability and accuracy.


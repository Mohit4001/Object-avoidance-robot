# Object-avoidance-robot
# Object Avoidance Robotic Car 🚗🤖

##  Project Overview
The **Object Avoidance Robotic Car** is an autonomous robotic vehicle designed to detect obstacles in its path and change direction automatically.  
It uses an **ultrasonic sensor** to measure distance and an **Arduino Uno** to process the data and control motor movement.

This project demonstrates the practical application of **embedded systems, sensors, and motor control** in robotics.

---

##  Components Used
- Arduino Uno  
- Ultrasonic Sensor (HC-SR04)  
- Motor Driver Module (L298N / L293D)  
- DC Motors  
- Robot Chassis  
- Wheels  
- Battery Pack  
- Jumper Wires  

---

## Working Principle
1. The ultrasonic sensor continuously measures the distance to objects in front of the robot.  
2. If the distance is greater than a defined threshold, the robot moves forward.  
3. When an obstacle is detected within the threshold distance:
   - The robot stops
   - Changes direction (left/right)
   - Continues moving to avoid collision  

This logic allows the robot to navigate autonomously without human intervention.

---

##  Features
- Automatic obstacle detection  
- Real-time distance measurement  
- Autonomous direction control  
- Simple and efficient logic  
- Suitable for beginners in robotics  

---

##  Programming Language
- Embedded C (Arduino IDE)


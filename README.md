# Cosmoclench-RC-Bot
A Remote control (RC) bot which is controlled wirelessly by Tx and Rx technique.

Component used
1.Arduino Uno or ESP32
2.Johnson motors
3.Motor Driver(L298N)
4.MDF board
5.Gears ( for claw mechanism)
6.Li-ion Batteries 
7.Battery Holder along with Battery charger
8.Servo motors( MG996 or SG90)
9.Wheels along with Belt
10.Jumpper wires 

This project consists of two main sections:

  Autonomous/Remote-Controlled Vehicle:
      - The bot is designed to navigate and complete a predefined track.
      - It has a four-wheel drive system controlled by a motor driver, which is interfaced with an Arduino Uno.
      - The bot can be controlled wirelessly using a remote. If an ESP32 is used, Bluetooth communication can be implemented for control.
      - The entire system is powered externally by Li-ion cells, ensuring efficient power management and mobility.

   Claw Mechanism for Object Manipulation:
      - The bot features a claw mechanism capable of picking up specific-sized cubes (serving as obstacles on the track).
      - The claw operates with precision to grip, lift, and place the cubes according to predefined requirements.
      - The mechanism can be actuated using servo or stepper motors for controlled movement.

This project aims to integrate robotics, wireless communication, and autonomous navigation, making it suitable for applications in automated material handling, obstacle removal, or competition-based robotic challenges.

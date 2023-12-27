# Obstacle Avoiding Robot with Arduino

Welcome to the guide on creating your very own obstacle-avoiding robot using Arduino! This project is beginner-friendly, requiring basic knowledge of Arduino. The robot utilizes an Arduino Uno R3 along with an L293D motor shield to drive its motors. The code is simple, and the circuit involves only a few wires, making it accessible for enthusiasts of all levels.

## Table of Contents
- [Parts Required](#parts-required)
- [Assemble the Chassis](#assemble-the-chassis)
- [Main Connections](#main-connections)
- [Arduino Code](#arduino-code)
- [Run](#run)

## Parts Required
Before we begin, gather the following components:
- Arduino
- L293D Motor Shield
- Chassis (including motors and wheels)
- Wires
- Battery holder
- Micro servo motor
- HC-sr04 ultrasonic sensor module
- Holding bracket for the sensor

## Assemble the Chassis
1. Assemble your robot body according to your chassis. Refer to the instruction manual if provided.
2. Attach Arduino, the motor shield, and the battery holder to the chassis.
3. Fix the servo motor at the front, with its head below the HC-sr04 bracket.
4. Place the sensor into the bracket, and attach the bracket to the servo motor.

**Note:** Don't permanently fix the sensor onto the servo motor to allow for adjustments if needed.

## Main Connections
Connect the components as follows:
- Make sensor connections according to the provided diagram.
- Connect the servo motor and DC motors to the motor shield.
- Connect the battery to the shield and the shield to the Arduino board.

## Arduino Code
The software aspect involves programming the Arduino. You can use the provided Arduino code as a reference or create your own. The code is available in the [Obstacle_Avoiding.ino](./Obstacle_Avoiding.ino) file.

## Run
Congratulations! You've successfully built your obstacle-avoiding robot. Now, it's time to experiment with the code and enjoy playing with your new robot. Have fun exploring the possibilities!

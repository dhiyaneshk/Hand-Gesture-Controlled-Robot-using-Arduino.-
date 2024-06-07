# Hand Gesture Controlled Robot

## Project Overview

This project involves the creation of a hand gesture-controlled robot using Arduino. The robot can be controlled by the gestures of the user's hand within a range of 10 meters. This technology aims to make the control of robotic systems more intuitive and user-friendly, potentially paving the way for future advancements where control might be possible through thoughts alone.

## Table of Contents
1. [Introduction](#introduction)
2. [Hardware Components](#hardware-components)
3. [Software Requirements](#software-requirements)
4. [Setup and Installation](#setup-and-installation)
5. [Usage](#usage)
6. [Contributors](#contributors)
7. [License](#license)

## Introduction

With the advancement in technology, there is a growing need for more efficient and time-saving methods for various tasks. This project explores the concept of controlling a robot using hand gestures, providing a more intuitive way to interact with robotic systems.

The system utilizes an Arduino Uno microcontroller, an accelerometer to detect hand gestures, and motor driver shields to control the wheels of the robot.

## Hardware Components

- Arduino Uno
- Accelerometer (Angle Detector)
- Motor Driver Shield
- Wireless Communication Modules
- Robot Chassis with Motors

## Software Requirements

- Arduino IDE
- Required Libraries (available in the `libraries` directory)

## Setup and Installation

1. **Hardware Setup:**
   - Assemble the robot chassis and attach the motors.
   - Connect the motor driver shield to the Arduino Uno.
   - Attach the accelerometer to the glove for gesture detection.
   - Ensure proper wiring between the accelerometer, Arduino, and wireless communication modules.

2. **Software Installation:**
   - Download and install the Arduino IDE from [here](https://www.arduino.cc/en/software).
   - Clone this repository to your local machine.
   - Open the Arduino IDE and install the required libraries from the `libraries` directory.

3. **Uploading the Code:**
   - Open the transmitter and receiver Arduino sketches located in the `transmitter` and `receiver` directories respectively.
   - Connect the Arduino to your computer and upload the respective codes to the transmitter and receiver modules.

## Usage

1. Power on the robot and the gesture controller (glove with accelerometer).
2. The robot should now respond to the hand gestures made by the user.
   - Move hand forward to drive forward.
   - Move hand backward to reverse.
   - Tilt hand left or right to turn the robot accordingly.

## Contributors

- **Dhiyanesh KV** - B.E (Electronics and Communication Engineering), Anna University, Chennai



# Arduino-and-OpenCV-based-follower-System

# Requirements * PySerial * OpenCV for Python

## Hardware Includes: * Arduino Uno * Chassis * Webcam * Motor Driver

This is the assembled chassis with a webcam.



## Configuration and Algorithm
The project builds an algorithm to detect humans by tracking faces using the OpenCV library and Python. The hardware is built around an Arduino microcontroller and an external webcam, which are linked via an intermediate personal computer where all image processing occurs. The Arduino and the webcam are both housed in a chassis.

Signals from the computer are serially communicated to the Arduino based on the position and size of the detected human face, which in turn controls the bot to move accordingly to keep tracking the human face.

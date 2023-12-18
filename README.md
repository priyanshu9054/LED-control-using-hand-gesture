# LED-control-using-hand-gesture
In this project we will control LEDs connected to arduino UNO board  using mediapipe and pyfirmata library

Introduction
This project demonstrates how to control an LED using hand gestures detected by MediaPipe and communicate with Arduino Uno using PyFirmata. By recognizing specific hand gestures, users can turn the LED on/off or perform other predefined actions.

Requirements
Arduino Uno
LED and resistor
Webcam
Python 3.x
PyFirmata
MediaPipe
Setup
Install Python Libraries:

bash
Copy code
pip install pyfirmata mediapipe
Upload Arduino Sketch:

Upload the led_control.ino sketch to your Arduino Uno.
Wiring:

Connect the LED and resistor to the designated pin on the Arduino Uno.

Usage
Gesture Recognition:

Hold your hand in front of the webcam.
Perform predefined gestures (e.g., open hand to turn on, closed fist to turn off).
LED Control:

The LED will respond to your hand gestures, turning on or off based on the recognition.
Customization:

Modify the led_control.py script to define additional gestures and corresponding actions.
File Structure
led_control.ino: Arduino sketch for LED control.
led_control.py: Python script for hand gesture recognition and communication with Arduino.
Dependencies
PyFirmata: Python interface for Firmata protocol.
MediaPipe: Hand tracking library for detecting hand gestures.

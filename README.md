# Radiosurgery-MotionTracker
This is a project I am working on with my design team, which uses an IMU sensor to gather movement signals and display cleaned data on a GUI for medical professionals to track movement. 

## Overview
MotionTracker is a Python application that reads and visualizes simulated wearable sensor (IMU) data in real time.  
This project demonstrates skills in signal processing, real-time data plotting, and GUI development using Tkinter and Matplotlib.

## Features
- Connect / disconnect IMU device (simulated)
- Start / stop real-time tracking
- Display live X, Y, Z translation and Yaw, Pitch, Roll orientation
- Save data to CSV
- Real-time plots of translation and orientation

## Tools & Libraries
- Python 3.12.11
- Tkinter (GUI)
- Matplotlib (real-time plotting)
- collections.deque (data buffering)
- CSV handling


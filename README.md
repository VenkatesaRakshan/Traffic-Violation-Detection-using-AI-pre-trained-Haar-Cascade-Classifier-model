

🚦 Traffic Signal Violation Detection System

This project is a computer vision–based Traffic Signal Violation Detection System developed using Python and OpenCV. The system detects traffic light states (Red, Yellow, Green) and monitors vehicles entering a predefined region during a red signal to identify violations.

🔍 Project Overview

The system performs:

Traffic light detection using HSV color thresholding

Circle detection using Hough Transform

Vehicle detection using Haar Cascade Classifier

Region of Interest (ROI) selection using mouse input

Automatic frame capture when a vehicle crosses during a red signal

If a vehicle is detected inside the selected ROI while the traffic light is red, the system saves the frame as violation evidence.

🧠 Techniques Used

OpenCV for image processing

HSV color segmentation for traffic light detection

Hough Circle Transform for signal confirmation

Haar Cascade (Viola–Jones algorithm) for vehicle detection

Rule-based logic for violation decision

⚙️ Technologies

Python

OpenCV

NumPy

Haar Cascade XML classifier

🚀 Features

Real-time video processing

Manual ROI selection using mouse

Multi-color traffic light detection (Red/Green/Yellow)

Automated violation frame capture

Simple and lightweight implementation (No deep learning required)

📌 Applications

Traffic monitoring systems

Smart city surveillance

Academic computer vision projects

Basic intelligent transportation systems

⚠️ Limitations

Uses classical Haar Cascade (not deep learning)

Manual ROI selection required

Performance depends on lighting conditions

No automatic number plate recognition

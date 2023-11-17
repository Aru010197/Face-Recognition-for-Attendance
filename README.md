# Face-Recognition-for-Attendance
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Overview

The Facial Recognition Attendance System is a Python-based project that leverages facial recognition technology to automate the attendance tracking process. This project uses OpenCV, NumPy, and face-recognition libraries to create a secure and efficient authentication system.

https://github.com/ageitgey/face_recognition 

## Features

- **Facial Recognition Authentication:**
  - Utilizes face-recognition AI model for scanning and recognizing human faces.
  - Establishes face recognition as an authentication mechanism for the attendance system.

- **Attendance Tracking:**
  - Tracks attendance by recognizing and marking the presence of known faces.
  - Generates a CSV file for each day with the recorded attendance.

- **Dependency Installation:**
  - Provides clear instructions for installing required Python packages using pip.

## Usage 
1.Run the Python script:

     python facial_recognition_attendance.py
2.Press 'q' to exit the application.

## Configuration
1. Update the known faces in the photos/ directory with images of individuals to be recognized.
2. Adjust the file path and name in the script for storing attendance data (default: current_date.csv).

## Dependencies
- OpenCV (opencv-python)
- NumPy (numpy)
- Face Recognition (face_recognition)

## License
This project is licensed under the MIT License.


<h1>🚗 DROWSY DRIVER DETECTION SYSTEM</h1>

This project is a real-time drowsy driver detection system using Flask, OpenCV, and Dlib. The system continuously monitors the driver's eye aspect ratio (EAR) to detect signs of fatigue, alerting the driver through an audio signal if drowsiness is detected.

<h3>📋 Features</h3>

Real-time monitoring of driver’s eyes through webcam.
Calculates Eye Aspect Ratio (EAR) to assess drowsiness.
Plays an alert sound when drowsiness is detected.
Web interface built using Flask.

<h3>🛠️ Tech Stack</h3>

Python

Flask for the web interface
OpenCV for video processing
Dlib for facial landmark detection
Imutils for efficient image manipulation
Pygame for sound alerts

<h3>🚀 How It Works</h3>

The system captures frames from the webcam.
Detects facial landmarks to identify the eyes.
Computes the Eye Aspect Ratio (EAR):
EAR drops below a set threshold when eyes are closing.
If the EAR remains below the threshold for a predefined time, an alert sound is triggered.

![image](https://github.com/user-attachments/assets/b08d44b2-2afe-49db-a1ee-245181f7ecad)


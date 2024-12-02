<h1>🚗 DROWSY DRIVER DETECTION SYSTEM</h1>

This project is a real-time drowsy driver detection system using Flask, OpenCV, and Dlib. The system continuously monitors the driver's eye aspect ratio (EAR) to detect signs of fatigue, alerting the driver through an audio signal if drowsiness is detected.

<h3>📋 Features</h3>

Real-time monitoring of driver’s eyes through webcam.<br>
Calculates Eye Aspect Ratio (EAR) to assess drowsiness.<br>
Plays an alert sound when drowsiness is detected.<br>
Web interface built using Flask.<br>

<h3>🛠️ Tech Stack</h3>

<b>Python</b><br>

Flask for the web interface<br>
OpenCV for video processing<br>
Dlib for facial landmark detection<br>
Imutils for efficient image manipulation<br>
Pygame for sound alerts<br>

<h3>🚀 How It Works</h3>

The system captures frames from the webcam.<br>
Detects facial landmarks to identify the eyes.<br>
Computes the Eye Aspect Ratio (EAR):<br>
EAR drops below a set threshold when eyes are closing.<br>
If the EAR remains below the threshold for a predefined time, an alert sound is triggered.<br>

![image](https://github.com/user-attachments/assets/b08d44b2-2afe-49db-a1ee-245181f7ecad)


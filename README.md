Hello , 
Here is my project called Driver Drowsiness Detection System
This project implements a real-time Driver Drowsiness Detection system using computer vision techniques. It monitors eye and mouth movements to detect signs of fatigue.

 Key Features
Detects faces using dlib and OpenCV

Calculates:
EAR (Eye Aspect Ratio) to detect eye closure
MAR (Mouth Aspect Ratio) to detect yawning

Triggers alerts when drowsiness is detected

Saves EAR, MAR, and timestamps into a CSV for further analysis

Plots EAR and MAR trends after session

 Dataset
Real-time webcam frames

Data from 7 different subjects (18,125 frames total)

 Tech Stack
Python

OpenCV

dlib (Facial landmark detection)

Matplotlib (Data visualization)

Pandas (CSV handling)

 How It Works
Captures video via webcam

Extracts eye & mouth landmarks

Computes EAR & MAR

Compares against thresholds

Triggers alarm if drowsiness is detected

Saves and visualizes results

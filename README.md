# Drowsiness Detection System 🚗💤
![Python](https://img.shields.io/badge/Python-3.6%2B-blue.svg) ![OpenCV](https://img.shields.io/badge/OpenCV-4.x-orange.svg) ![Keras](https://img.shields.io/badge/Keras-2.x-red.svg)

## 🚗 Keeping Roads Safe with AI  
A real-time **Driver Drowsiness Detection System** built with **Python**, **OpenCV**, and **Keras**. This project leverages computer vision and deep learning to monitor a driver’s eyes and sound an alarm when drowsiness is detected—helping prevent accidents caused by sleepy driving.  

> **Why it matters**: Drowsy driving is a major cause of road accidents, especially for long-haul drivers. This system acts as a vigilant co-pilot!

## 📌 Overview
The **Drowsiness Detection System** is an AI-powered project designed to detect driver fatigue and alert them in real time. The system uses a webcam to monitor facial landmarks and eye movements, identifying signs of drowsiness and triggering alerts to prevent accidents.

## ✨ Features 
- **Real-time face detection** using OpenCV.
- **Eye aspect ratio (EAR) calculation** for detecting drowsiness.
- **Sound alert system** to wake the driver.
- **Compatible with any standard webcam.**
- **Easy to use and lightweight.**

## 🛠️ Technologies Used 
- **Python**
- **OpenCV** (for image processing)
- **Dlib** (for facial landmark detection)
- **NumPy** (for mathematical computations
- **Pygame** (for playing alert sounds)

## 📂 Dataset
📥 **Download Dataset**: [YawnEye](https://www.kaggle.com/datasets/serenaraju/yawn-eye-dataset-new)


## 🏗️ Installation 
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Real-time-Drowsiness-Detection-using-ML.git
   cd drowsiness-detection

## 🧑‍💻 How It Works 
1. The webcam captures real-time video feed.
2. The system detects the face and eyes using Dlib's facial landmarks.
3. The **Eye Aspect Ratio (EAR)** is calculated:
   - If EAR falls below a threshold for a certain duration, the system detects drowsiness.
   - A warning alert (sound) is triggered to wake the driver.

## 🎯 Features  
- **Real-Time Monitoring**: Captures live video from a webcam.  
- **Eye State Detection**: Uses a CNN to classify eyes as "Open" or "Closed."  
- **Drowsiness Scoring**: Tracks eye closure duration and triggers an alert at a customizable threshold.  
- **Audio Alert**: Plays `alarm.wav` when drowsiness is detected.  
- **Visual Cues**: Displays status and score on-screen with a red border during alerts.



🚀   **Stay alert, drive safe!**

## Project Directory
![Screenshot 2025-02-25 183549](https://github.com/user-attachments/assets/ab290112-8253-42a3-8b1a-2f9cfc07d96e)


---



 


# WakeSense AI – Adaptive Real-Time Drowsiness Detection System

## About the Project

WakeSense AI is a real-time drowsiness detection system built using Computer Vision and facial landmark tracking. The application monitors eye movements through a webcam and detects signs of fatigue by analyzing blink patterns, eye closure duration, and behavioral trends.

The system goes beyond simple threshold-based detection by adapting to individual user behavior over time. It learns from user feedback, adjusts alert sensitivity, and aims to reduce false alarms while maintaining reliable detection.

This project was developed to explore the practical application of Computer Vision, real-time monitoring systems, and adaptive learning techniques in safety-critical scenarios such as driver monitoring and fatigue detection.

---

## Features

* Real-time face and eye tracking using MediaPipe Face Mesh
* Eye Aspect Ratio (EAR) based drowsiness detection
* Detection of prolonged eye closure and abnormal blink patterns
* Adaptive threshold adjustment based on user behavior
* Sleep probability estimation using multiple indicators
* Audio alarm system for immediate alerts
* User feedback mechanism to improve future detection
* Session statistics and monitoring information
* Persistent user profile storage for personalized performance

---

## Technologies Used

### Programming Language

* Python

### Libraries

* OpenCV
* MediaPipe
* NumPy
* SciPy
* Pygame

### Core Concepts

* Computer Vision
* Facial Landmark Detection
* Real-Time Processing
* Human State Monitoring
* Adaptive Learning
* Behavioral Analysis

---

## How It Works

1. The webcam captures a live video stream.
2. MediaPipe Face Mesh detects facial landmarks in real time.
3. Eye landmarks are extracted to calculate the Eye Aspect Ratio (EAR).
4. Blink behavior and eye closure duration are continuously monitored.
5. Multiple factors are combined to estimate the user's drowsiness level.
6. When fatigue indicators exceed safe limits, an alarm is triggered.
7. User feedback is stored and used to improve future detection accuracy.

---

## Key Highlights

* Fully real-time processing with live webcam input.
* Personalized alert thresholds that adapt over time.
* Early drowsiness pattern detection instead of relying solely on eye closure.
* Audio and visual alert mechanisms.
* Lightweight implementation that runs locally without cloud services.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/wakesense-ai.git
cd wakesense-ai
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python main.py
```

---

## Possible Future Improvements

* Deep Learning-based fatigue prediction
* Yawning detection
* Head pose tracking
* Mobile and embedded device support
* Cloud dashboard for analytics
* Multi-user support
* Driver safety monitoring integration

---

## Use Cases

* Driver drowsiness monitoring
* Workplace fatigue detection
* Student attention monitoring during long study sessions
* Industrial safety applications
* Health and wellness monitoring systems

---

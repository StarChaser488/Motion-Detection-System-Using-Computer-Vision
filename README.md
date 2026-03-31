# Motion Detection System using Computer Vision

## Overview
This project is a real-time Motion Detection System developed using Computer Vision techniques in Python. The system captures live video from a webcam and detects motion by analyzing differences between consecutive frames.

It processes each frame using image processing techniques such as grayscale conversion, Gaussian blurring, and frame differencing to identify changes in the scene. When motion is detected, the system highlights the moving region using bounding boxes in the video stream.

This project demonstrates the practical application of computer vision in surveillance and monitoring systems and is designed to be simple, efficient, and beginner-friendly.

---

## Objectives
- To build a real-time motion detection system using OpenCV
- To understand frame processing and image transformation techniques
- To implement basic computer vision algorithms
- To develop a lightweight surveillance prototype

---

## Features
- Real-time video capture using webcam
-  Accurate motion detection using frame differencing
- Highlights moving objects with bounding boxes
- Fast and efficient processing
- Uses basic image processing techniques (no heavy ML required)
- Easy to run on low-end systems
- Clean and modular code structure

---

##  Technologies Used
- **Python 3.12** – Core programming language  
- **OpenCV** – Image processing and computer vision  
- **NumPy** – Numerical operations and array handling

##  Algorithm

1. Start webcam video capture
2. Read two consecutive frames
3. Convert frames to grayscale
4. Apply Gaussian Blur
5. Calculate difference between frames
6. Apply threshold to highlight motion
7. Find contours
8. Draw bounding boxes on detected motion
9. Display output frame

## Future Scope

- Integrate deep learning for object classification
- Add face recognition
- Send alerts via email or SMS
- Store motion recordings
- Deploy as a web application
---

##  Project Structure
motion-detection/
│── main.py
│── README.md

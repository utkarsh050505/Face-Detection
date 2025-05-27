# 👁️ Real-Time Face Detection using OpenCV

This project demonstrates a real-time face detection system using **Haar Cascade Classifiers** with OpenCV on a standard webcam. It serves as a foundational step in the field of computer vision, enabling further exploration into more advanced machine learning techniques such as CNN-based detection, face recognition, emotion classification, and real-time video analytics.

## 🧠 Project Context

This project was developed as part of my journey to understand practical applications of classical computer vision techniques before transitioning into deep learning-based models. It reflects my growing interest in machine learning and my hands-on experience with image processing, camera interfacing, and real-time inference pipelines.

## 🚀 Objectives

- Build a lightweight real-time face detector
- Understand Haar Cascade working principles
- Use OpenCV to process webcam video streams
- Create a modular base for future ML/CV experiments

## 🔧 Tech Stack

- **Language:** Python 3.x  
- **Libraries:** 
  - [OpenCV](https://opencv.org/) – for image capture and processing  
  - [Haar Cascades](https://docs.opencv.org/master/d7/d00/tutorial_meanshift.html) – for face detection  

## 💡 How it Works

1. The webcam feed is captured frame by frame.
2. Each frame is converted to grayscale.
3. A pre-trained Haar Cascade classifier detects faces in the frame.
4. Detected faces are highlighted with bounding boxes in real-time.

# Real-Time Facial Emotion Detection

This project implements a facial emotion recognition system using deep learning and computer vision.  
The model is trained on a labeled facial expression dataset and is used to predict human emotions in real time through a webcam feed.

The complete implementation, including training and real-time inference, is done using Python and Jupyter Notebooks.

---

## 🚀 Features
- Facial emotion recognition using a CNN-based deep learning model
- Real-time emotion detection using webcam input
- Face detection using OpenCV
- Emotion classification for detected faces
- Implemented end-to-end using Python

---

## 🛠 Tech Stack
- Python  
- OpenCV  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 📊 Dataset
- Public facial emotion recognition dataset
- Approximately **35,000 facial images**
- Images categorized into emotion classes:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Sad
  - Surprise
  - Neutral
- Dataset not uploaded to this repository due to size limitations

---

## 🧠 Model Training
- Training implemented in `Training.ipynb`
- Images preprocessed by:
  - Converting to grayscale
  - Resizing to fixed dimensions
  - Normalization
- Convolutional Neural Network (CNN) architecture used
- Model trained using categorical cross-entropy loss
- Accuracy used as the primary evaluation metric

---

## 🎥 Real-Time Emotion Detection
- Implemented in `Realtime_Emotion_Detection.ipynb`
- Uses OpenCV Haar Cascade for face detection
- Captures live webcam feed
- Detects face regions and predicts emotion for each face
- Emotion label displayed on the video stream in real time

---

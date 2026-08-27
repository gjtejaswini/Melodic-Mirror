# 🎵 Melodic Mirror

Melodic Mirror is an AI-powered emotion-based music recommendation system that
uses a webcam to analyse a user's facial expressions and identify their
emotional state.

The system uses computer vision and a Convolutional Neural Network (CNN)
trained on the FER2013 dataset to recognize facial emotions. Based on the
detected emotion, the application categorizes the user's mood and recommends
songs from predefined music lists.

## 🚀 Features

- Real-time facial expression detection using a webcam
- Emotion classification using a CNN-based model
- Computer vision processing using OpenCV
- Emotion classification into positive, negative, and neutral categories
- Mood-based song recommendations
- Real-time interaction through the webcam

## 🛠️ Technologies Used

- Python
- OpenCV
- Convolutional Neural Network (CNN)
- FER2013 Dataset
- Machine Learning / Deep Learning
- Computer Vision

## ⚙️ How It Works

1. The webcam captures the user's facial image.
2. OpenCV processes the captured frame.
3. The facial region is detected and provided to the trained CNN model.
4. The model predicts the user's facial emotion.
5. The detected emotion is categorized into a mood.
6. The system recommends suitable songs from predefined lists.

## 🎯 Objective

The objective of Melodic Mirror is to create an interactive system that
combines facial emotion recognition with personalized music recommendations
to provide a mood-aware user experience.

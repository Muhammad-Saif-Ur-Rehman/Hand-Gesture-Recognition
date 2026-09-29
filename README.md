# ✋ Hand Gesture Recognition with CNN

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?logo=Jupyter&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-green)

A real-time computer vision and deep learning project that identifies and classifies hand gestures using a webcam feed. The core of this project is a custom Convolutional Neural Network (CNN) trained on a hand gesture dataset to achieve robust, real-time predictions.

## 🌟 Key Features

* **CNN-Based Classification:** Utilizes a Convolutional Neural Network built and trained specifically to recognize distinct hand gesture classes.
* **Real-Time Inference:** Captures live video feed through the camera, preprocessing frames on the fly and passing them through the trained model for instant classification.
* **Interactive Development:** Fully contained within Jupyter Notebooks, clearly separating the model training pipeline from the real-time deployment script.

## 📂 Repository Structure

```text
├── .gitattributes                          # Git configuration for file formatting
├── Hand_Gesture_Recognition.ipynb          # EDA, data preprocessing, and CNN model training
├── Real time gestures recognition.ipynb    # OpenCV webcam integration for live CNN inference
└── README.md                               # Project documentation

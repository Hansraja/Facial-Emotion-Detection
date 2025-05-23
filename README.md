# Facial Emotion Detection Using Deep Learning

This project implements a facial emotion detection system using deep convolutional neural networks (CNNs) trained on the FER-2013 dataset. It classifies human facial expressions into five categories: **Angry**, **Happy**, **Sad**, **Surprise**, and **Neutral**.

![emotion-detection](https://user-images.githubusercontent.com/your-username/your-emotion-image.png) <!-- Optional: Add a sample result image -->

## 🚀 Project Overview

Facial emotion detection has become a significant area of research with the advent of powerful GPUs and deep learning. This project focuses on building a robust model capable of recognizing emotional states from grayscale facial images using CNN.

### 🔍 Key Features

- Capture and preprocess static facial images.
- Extract features using deep neural networks.
- Use Convolutional Neural Networks (CNN) for classification.
- Trained on the FER-2013 dataset published at ICML.
- Recognizes five facial emotions:
  - 😠 Angry
  - 😀 Happy
  - 😐 Neutral
  - 😢 Sad
  - 😲 Surprise

---

## 📊 Dataset

**FER-2013 Dataset**  
- 35,887 grayscale images of size 48x48 pixels.
- Pre-split into:
  - Training: 28,709 images
  - Test: 7,178 images
- Each image is labeled as one of the following emotions:
  - Happy, Sad, Angry, Afraid, Surprise, Disgust, Neutral
- In this project, only the following 5 emotions are used:
  - Angry, Happy, Sad, Surprise, Neutral

[Link to Dataset on Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas
- Matplotlib / Seaborn

---

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/hansraja/facial-emotion-detector-cnn.git
   cd Facial-Emotion-Detection/

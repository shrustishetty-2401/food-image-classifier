# 🍔🍕 Food Image Classifier (CNN)

A deep learning project that classifies food images (pizza, burger, etc.) using a Convolutional Neural Network (CNN) built with TensorFlow.

---

## 🧠 Project Overview

This project trains a CNN model to recognize food images from different categories.  
It demonstrates how image data is processed, normalized, and used for classification tasks in deep learning.

---

## ⚙️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.11-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Keras](https://img.shields.io/badge/Keras-DeepLearning-red)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

- Python
- TensorFlow / Keras
- CNN (Convolutional Neural Networks)
- Jupyter Notebook

---

## 📁 Dataset

- Custom dataset created manually (pizza 🍕, burger 🍔, etc.)
- Images loaded using `image_dataset_from_directory`
- Resized to 224x224 and normalized

---

## 🧱 Model Architecture

- Conv2D (32 filters)
- MaxPooling2D
- Conv2D (64 filters)
- MaxPooling2D
- Conv2D (128 filters)
- Flatten
- Dense (128)
- Dense (Softmax output)

---

## 📊 Training Results

> ⚠️ Replace these numbers with your actual results after training

- Accuracy: ~XX%
- Loss: ~XX
- Epochs: 3–10

---

## 📈 Sample Prediction

Add sample image predictions here later:

```python
model.predict(new_image)
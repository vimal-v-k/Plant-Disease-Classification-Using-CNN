# 🌿 Plant Disease Classification using CNN

This project classifies plant leaf images into categories such as healthy or diseased using a Convolutional Neural Network (CNN). The model is built with TensorFlow and Keras, using image preprocessing, training callbacks, and visualization tools to improve performance and monitor training.

## 🧠 Model Summary

- Framework: TensorFlow / Keras
- Architecture:
  - Conv2D
  - MaxPooling2D
  - BatchNormalization
  - Dropout
  - Flatten
  - Dense
- Image Size: 150x150
- Batch Size: 32
- Callbacks: EarlyStopping, ReduceLROnPlateau, TensorBoard

## ✅ Features

- ImageDataGenerator for normalization and preprocessing
- Model training with validation data
- Accuracy and loss plots
- TensorBoard support for visualization

## 📦 Requirements

Install dependencies with:
pip install -r requirements.txt

## 🚀 How to Run

1. Open the notebook:
   jupyter notebook plant_disease_classification_using_cnn_v1.ipynb
2. Run all the cells to train and evaluate the model.

## 📊 Output

- Training and validation accuracy/loss graphs
- Confusion matrix
- Sample predictions on test images

## 📄 License

MIT License

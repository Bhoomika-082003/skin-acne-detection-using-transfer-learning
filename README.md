# Skin Acne Detection Using Transfer Learning

## Overview
This project is a deep learning-based binary image classification system that detects Acne vs Normal Skin using transfer learning.

## Dataset
Kaggle Skin Disease Detection Dataset

## Model Architecture
- Base Model: MobileNetV2 (pretrained on ImageNet)
- Technique: Transfer Learning
- Top Layers: GlobalAveragePooling + Dense + Dropout
- Output Layer: Sigmoid (Binary Classification)

## Tools & Technologies
- Python
- TensorFlow / Keras
- Google Colab
- Kaggle Dataset
- GitHub

## Results
- Validation Accuracy: 1.0
- Binary Classification: Acne / Normal Skin

## How to Use
1. Load the trained model (.keras file)
2. Preprocess input image (resize to 224x224)
3. Predict using model.predict()

## Purpose
This project demonstrates practical implementation of deep learning for dermatology-based image classification.

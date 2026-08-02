# Skin Acne Detection Using Transfer Learning

## Overview
A deep learning-based binary image classification system that classifies images as Acne or Normal Skin, using transfer learning on a pretrained MobileNetV2 backbone.

## Dataset
Kaggle Skin Disease Detection Dataset

## Model Architecture
- **Base Model:** MobileNetV2 (pretrained on ImageNet)
- **Technique:** Transfer Learning
- **Top Layers:** GlobalAveragePooling + Dense + Dropout
- **Output Layer:** Sigmoid (Binary Classification)

## Tools & Technologies
- Python
- TensorFlow / Keras
- Google Colab
- Kaggle Dataset
- GitHub

## Results
The model was evaluated on a held-out validation split of the dataset. **Note:** validation accuracy on this run was very high, which may reflect properties of this specific dataset (e.g., limited size, visual similarity within classes, or potential overlap between train/validation samples) rather than fully generalizable performance. Results should be interpreted with appropriate caution and would benefit from evaluation on an independent, larger, and more diverse test set before drawing strong conclusions.

## How to Use
1. Load the trained model (`.keras` file)
2. Preprocess input image (resize to 224x224)
3. Predict using `model.predict()`

## Purpose
This project was built as a practical exercise in applying transfer learning to a dermatology-related image classification task, and in setting up an end-to-end training/evaluation pipeline in TensorFlow/Keras.

## Limitations
This is an educational/practice project, not a validated diagnostic tool. It has not been tested on external datasets, has not been clinically validated, and should not be used for any real diagnostic purpose.

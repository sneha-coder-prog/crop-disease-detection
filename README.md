# crop-disease-detection
AI-based crop disease detection system
## Overview

This project is a Deep Learning based Plant Disease Detection system built using TensorFlow and MobileNetV2. The model classifies potato plant leaf images into:

Healthy
Diseased

The project also includes Grad-CAM visualization for model explainability.

## Dataset

Dataset used: PlantVillage Dataset

Classes used:

Potato___healthy
Potato___Early_blight
Potato___Late_blight

Disease classes are merged into a single Diseased class.

## Technologies Used
Python
TensorFlow / Keras
MobileNetV2
OpenCV
Albumentations
NumPy
Pandas
Matplotlib
Scikit-learn
Features
Transfer Learning using MobileNetV2
Data Augmentation
Binary Classification
Confusion Matrix & Classification Report
Grad-CAM Visualization
Early Stopping & Model Checkpointing
Model Performance
Metric	Score
Test Accuracy	99.69%
Healthy F1-Score	99.83%
Diseased F1-Score	97.87%
Grad-CAM

Grad-CAM is used to visualize infected regions of the leaf that influence the model prediction, improving interpretability of the system.

Future Improvements
Multi-class disease detection
Web application deployment
Mobile integration
Support for more plant species

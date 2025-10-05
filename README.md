# PlantChief_Application
AI Powered Plant Disease Detection System

This is an end-to-end deep learning pipeline for diagnosing plant leaf diseases using Convolutional Neural Networks (CNNs) and deploying them via a FastAPI backend with a React Native mobile application.
It enables real-time image-based disease prediction for multiple crops — including Apple, Corn, Tomato, Potato, Grape, Cherry, Bell Pepper, Strawberry and Peach — by serving optimized TensorFlow Lite (TFLite) models through a centralized inference server.

# Model Pipeline
Data Collection & Preprocessing

Image resizing, normalization, and extensive augmentation

Model Training (Custom CNN architectures trained per crop)

Quantization

FastAPI Integration

Mobile App Integration (React Native app for image upload and prediction visualization)

# Pipeline Overview

<img width="1440" height="1024" alt="Desktop - 1" src="https://github.com/user-attachments/assets/579e79ab-926a-496b-9940-191275aa1434" />


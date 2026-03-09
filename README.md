# Medical Imaging — CT Image Segmentation (U-Net Variants)

This project trains deep learning models to segment regions of interest in CT medical images using the BRISC2025 dataset.

## What I built
- Implemented a baseline **U-Net** segmentation model in **TensorFlow/Keras**
- Tested transfer-learning variants: **U-Net + MobileNetV2** and **U-Net + ResNet50**
- Evaluated models using **Dice Score** and **IoU**, and compared inference latency and parameter counts

## Key results (from experiments)
- Best performance reached approximately **Dice ~0.88** and **IoU ~0.79** (varies by backbone and setup)

## Tech stack
Python, TensorFlow/Keras, NumPy, OpenCV, Matplotlib (developed in Google Colab)

## Files
- `Medical_Imaging.ipynb` — training, evaluation, and visualizations
- `Deep Learning Driven Image Segmentation for Enhanced Diagnostic Accuracy in Medical Imaging.pdf` — project report

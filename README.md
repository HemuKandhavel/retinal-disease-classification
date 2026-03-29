# Automated OCT-Based Retinal Disease Classification

An end-to-end deep learning pipeline to classify retinal diseases from OCT scans using ResNet-18, with Grad-CAM explainability for clinical interpretability.

## Overview
Retinal diseases affect millions globally and require early diagnosis for effective treatment. This project automates classification of OCT images across 8 disease categories using deep learning, while making predictions interpretable for clinical use through Grad-CAM visualization.

## Tech Stack
- Python, TensorFlow, Keras
- ResNet-18 (transfer learning)
- Grad-CAM (explainability)
- OpenCV (image preprocessing)

## Features
- Classifies OCT images into 8 retinal disease categories
- ROI segmentation and feature extraction pipeline
- Grad-CAM heatmaps highlight affected retinal regions
- Disease severity estimation using model confidence scores (~89%)
- Clinically interpretable outputs to support early diagnosis

## Results
| Metric | Value |
|--------|-------|
| Disease categories | 8 |
| Model confidence (sample) | ~89% |
| Explainability method | Grad-CAM |


## Author
**Hema Priya K**  

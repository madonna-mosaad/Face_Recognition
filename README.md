# Face Detection and Recognition System

This project is a modular face detection and recognition system developed using Python and OpenCV. It includes comprehensive performance analysis and visualization capabilities.

## 📌 Table of Contents
- [Project Overview](#project-overview)
- [Face Detection](#face-detection)
- [Face Recognition](#face-recognition)
- [Performance Analysis](#performance-analysis)
- [Results](#results)
- [Team](#team)
- [Supervision](#supervision)

## 📖 Project Overview

The goal of this project is to detect and recognize human faces in images, and to evaluate the performance of the implemented recognition pipeline. The system consists of three main modules:

1. **Face Detection**
2. **Face Recognition**
3. **Performance Evaluation**

https://github.com/user-attachments/assets/a538d256-b7ed-4a94-bf30-930ce85fc0c0

## 🧠 Face Detection

Implemented using OpenCV’s Haar Cascade Classifier. The process includes:
- Grayscale image conversion
- Multi-scale detection
- Visualization with bounding boxes

## 🧬 Face Recognition

Uses a PCA-based model:
- Image preprocessing (resizing, CLAHE, normalization)
- Dimensionality reduction with Principal Component Analysis
- Cosine similarity for face matching

Model components:
- `pca_mean.npy`
- `pca_std.npy`
- `pca_components.npy`
- `pca_embeddings.npy`
- `label_map.json`

## 📊 Performance Analysis

We evaluated the recognition model using:
- **Accuracy**: 97.5%
- **Precision**: 98.3%
- **Recall**: 97.5%
- **F1-Score**: 97.3%
- **Specificity**: 99.9%
- **AUC Score**: 92.3%

Also included:
- ROC Curve
- Confusion Matrix

> ⚠️ Note: High performance is influenced by a limited dataset (20 subjects), which may not generalize to real-world scenarios.

## 👥 Team

- **Madonna Mosaad**
- **Nariman Ahmed**
- **Nancy Mahmoud**
- **Yassien Tawfik**

## 🧑‍🏫 Supervision

- Dr. Ahmed Badawy  
- Eng. Omar Hesham  
- Eng. Yara Wael  

## 📌 Course

Computer Vision (SBE3230), Faculty of Engineering – Cairo University

# 🧠 Brain Tumor Classification using PyTorch (Custom CNN architecture)

This repository contains a **PyTorch implementation** of a custom deep learning model for classifying brain tumors from MRI scans. The project demonstrates an **end-to-end machine learning pipeline**, covering everything from data acquisition and preprocessing to model training, evaluation, and visualization.

---

## 📋 Project Overview

The primary goal of this project is to accurately classify brain MRIs into one of **four categories**:

- **Glioma**
- **Meningioma**
- **Pituitary Tumor**
- **No Tumor**

We build a **custom Convolutional Neural Network (CNN)** from scratch to achieve high accuracy, showcasing the potential of tailored architectures in medical diagnostics.

---

## 📂 Dataset

This project uses the **[Brain Tumor Classification (MRI)](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)** dataset, which is publicly available on Kaggle.

---

## ✨ Key Features

- **🧾 Data Loading**: Downloads the dataset directly from Kaggle using the `kagglehub` library.
- **🖼️ Image Preprocessing**: Applies a series of transformations including **resizing**, **augmentation** (rotation, flipping), and **normalization**.
- **🧠 Custom CNN Architecture**: Utilizes a **custom-built CNN** designed specifically for this classification task.
- **📊 Comprehensive Evaluation**: Measures model performance with **loss/accuracy curves**, **confusion matrix**, and **sample prediction visualizations**.

---

## 🚀 Workflow Summary

The project follows a structured machine learning pipeline:

1. **Data Acquisition**  
   The Brain MRI dataset is downloaded from Kaggle and structured into training and testing directories.

2. **Preprocessing & Data Loaders**  
   Images are transformed using `torchvision.transforms` and loaded with `DataLoader`.

3. **Model Training**  
   A custom CNN model is trained over multiple epochs and metrics are logged.

4. **Results Visualization**  
   After training, the following visual outputs are generated:
   - 📉 **Loss & Accuracy Curves**
   - 🧾 **Confusion Matrix**
   - 🧩 **Grid of Predictions** with true vs. predicted labels

---

## 🎯 Results

The final model achieves a test accuracy of **over 96%**, proving that:

- 🧬 A well-designed custom CNN architecture can be highly effective for medical imaging tasks, learning features from scratch with remarkable precision.

---

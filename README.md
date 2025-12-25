# Cassava Leaf Disease Classification using CNN

This project focuses on detecting and classifying cassava leaf diseases using a Convolutional Neural Network (CNN).  
The goal is to help farmers and agricultural experts identify plant diseases early using image-based analysis.

---

## 📌 Project Overview

Cassava is an important food crop in many countries, but it is highly affected by various leaf diseases.  
This project uses deep learning techniques to classify cassava leaf images into different disease categories.

---

## 📂 Dataset

The dataset used is the **Cassava Leaf Disease Classification Dataset** from Kaggle.

### Classes:
- Cassava Bacterial Blight (CBB)
- Cassava Brown Streak Disease (CBSD)
- Cassava Green Mottle (CGM)
- Cassava Mosaic Disease (CMD)
- Healthy

---

## ⚙️ Project Workflow

1. Data loading and preprocessing  
2. Image resizing and normalization  
3. CNN model building  
4. Model training and validation  
5. Performance evaluation  

---

## 🧠 Model Architecture

The model uses a Convolutional Neural Network (CNN) consisting of:
- Convolution layers for feature extraction  
- MaxPooling layers to reduce dimensionality  
- Dropout layers to prevent overfitting  
- Fully connected dense layers for classification  

The model is trained using the **Adam optimizer** and **categorical cross-entropy loss**.

---


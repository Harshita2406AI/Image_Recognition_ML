# Image_Recognition_ML
Developed and deployed a CNN-based image recognition model in Python using TensorFlow and Keras, covering dataset preprocessing, optimization, and transfer learning for accurate real-world image classification.
# Image Recognition with Convolutional Neural Networks (CNN)

## Overview
This project is the outcome of a 5-day intensive bootcamp focused on building a complete image recognition pipeline — from data preprocessing to model deployment.  
Using **Convolutional Neural Networks (CNNs)**, the model can classify images with high accuracy on benchmark datasets such as **MNIST** (handwritten digits) and **CIFAR-10** (colored objects).  
The workflow also includes advanced techniques like **data augmentation**, **dropout regularization**, **transfer learning** with pre-trained models (MobileNetV2), and robust model evaluation.

---

## Objectives
- Understand and implement CNN architectures for image classification.
- Apply preprocessing, normalization, and data augmentation.
- Train, evaluate, and fine-tune models on real datasets.
- Use transfer learning to improve performance on smaller datasets.
- Visualize metrics such as accuracy curves, confusion matrices, and ROC curves.
- Save trained models and prepare them for deployment.

---

## Approach

### **1. Data Preparation**
- Downloaded datasets from **Kaggle** using Kaggle API.
- Normalized pixel values and reshaped data for CNN compatibility.
- Performed **Exploratory Data Analysis (EDA)** to understand dataset distribution.

### **2. Model Development**
- Built custom CNN architectures with:
  - Convolution + MaxPooling layers for feature extraction.
  - Dropout layers to reduce overfitting.
  - Batch normalization for faster, more stable training.
  - Dense layers with **Softmax** for multi-class classification.
- Experimented with **Transfer Learning** (MobileNetV2) for Cats vs Dogs classification.

### **3. Training**
- Used Adam optimizer with categorical cross-entropy loss.
- Trained models for multiple epochs with validation splits.
- Applied **Data Augmentation** (rotation, shifting, flipping) to enhance generalization.

### **4. Evaluation**
- Calculated accuracy, precision, recall, and F1-score.
- Plotted:
  - **Loss & Accuracy curves**
  - **Confusion matrices**
  - **ROC curves**
- Visualized **sample predictions** vs. expected outputs.

### **5. Deployment Preparation**
- Saved models in `.h5` format.
- Organized scripts, visualizations, and documentation.
- Uploaded to **GitHub** with a professional README for portfolio use.

---

## Results

### **MNIST CNN**
- Test Accuracy: **~99%**
- Model Size: **~2 MB**
- Example Predictions:  


### **CIFAR-10 CNN**
- Test Accuracy: **~85%**
- Strong performance on most classes, minor confusion between similar objects.

### **Cats vs Dogs (Transfer Learning with MobileNetV2)**
- Test Accuracy: **~95%**
- ROC-AUC: **0.97**
- Example ROC Curve:  

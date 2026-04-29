# Pretrain-Model

This project implements a Brain Tumor Classification System using Transfer Learning with deep learning models. It classifies MRI brain images into four categories: Glioma, Meningioma, Pituitary Tumor, and No Tumor.

📌 Project Overview

Brain tumors are life-threatening conditions that require early detection. This project uses Convolutional Neural Networks (CNNs) and pretrained models to automatically classify brain MRI images.

We leverage MobileNetV2 and VGG16 architectures to improve accuracy and reduce training time using transfer learning.

📂 Dataset

The dataset is divided into:

Brain/
 ├── Training/
 │    ├── glioma
 │    ├── meningioma
 │    ├── pituitary
 │    └── notumor
 │
 └── Testing/
      ├── glioma
      ├── meningioma
      ├── pituitary
      └── notumor
Total Classes: 4
Image Size: 224 x 224
Training, Validation, and Testing split used
⚙️ Technologies Used
Python 🐍
TensorFlow / Keras
NumPy
Matplotlib & Seaborn
Scikit-learn
🧠 Models Used
1. MobileNetV2
Pretrained on ImageNet
Base layers frozen
Custom dense layers added
Achieved ~90%+ validation accuracy
2. VGG16
Deep CNN architecture
Transfer learning applied
Added Batch Normalization & Dropout layers
🔄 Workflow
Dataset Extraction and Loading
Data Preprocessing & Augmentation
Model Building using Transfer Learning
Training & Validation
Model Evaluation
Prediction on Test Images
Performance Visualization
📊 Results
High training and validation accuracy achieved
Model evaluated using:
Accuracy & Loss graphs
Confusion Matrix
Test dataset predictions performed
📈 Visualizations
Training vs Validation Accuracy Graph
Training vs Validation Loss Graph
Confusion Matrix Heatmap
🚀 How to Run
Clone the repository:
git clone https://github.com/your-username/brain-tumor-classification.git
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook
Open and execute:
Brain Pretrain Model.ipynb
📌 Features
Multi-class classification
Transfer Learning for better performance
Data Augmentation to prevent overfitting
GPU support for faster training
Visualization of model performance

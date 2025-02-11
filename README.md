# 🖼️ Image Classification

## 📌 Project Overview
This project implements a **multi-class image classification model** using **PyTorch** and **transfer learning** (ResNet-18).  
It classifies images into different categories using a pre-trained model.

## 📂 Dataset
- The dataset contains images organized in folders, where each folder represents a different type of animal class
- The images were collected through **web scraping** from various sources. https://github.com/Zahraa28/animal-image-dataset 
- Data augmentation and preprocessing techniques (resizing, normalization) were applied.

## ⚡ Model Details
- **Architecture**: ResNet-18 (Pre-trained on ImageNet)
- **Loss Function**: CrossEntropyLoss
- **Optimizer**: Adam (Learning rate = 0.001)
- **Training**: 10 epochs, batch size = 32
- **Performance**: Achieved [your accuracy] accuracy

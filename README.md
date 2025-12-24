# FishNet: Fish Species Classification Using Deep Learning 🐟

## 📌 Project Overview
FishNet is a lightweight deep learning-based image classification system designed to accurately identify fish species from images. The model enhances MobileNetV3Small with a custom lightweight self-attention mechanism and residual dense blocks to achieve high accuracy while remaining efficient for mobile and edge deployment.

## 🚀 Features
- 31 fish species classification
- Lightweight architecture (MobileNetV3 + Attention)
- High accuracy with fewer parameters
- Suitable for mobile and edge devices

## 🧠 Model Architecture
- MobileNetV3Small backbone
- Lightweight self-attention (GhostModule-inspired)
- Residual Dense Block
- Spatial Dropout + Global Average Pooling

## 📊 Dataset
- Total images: 13,321
- Classes: 31 fish species
- Source: Kaggle Fish Dataset  
🔗 https://www.kaggle.com/datasets/markdaniellampa/fish-dataset

## 🛠 Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas
- OpenCV
- Scikit-learn
- Matplotlib, Seaborn

## 📈 Results
- Test Accuracy: **98.35%**
- Macro F1-score: **0.98**
- Outperformed ResNet50, InceptionV3, Xception

### Sample Outputs:
- Accuracy & Loss Curves
- Confusion Matrix
- ROC Curves
- Random Test Predictions

## 🏃 How to Run
```bash
pip install -r requirements.txt

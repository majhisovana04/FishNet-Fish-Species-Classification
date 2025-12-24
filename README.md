# FishNet – Fish Species Classification Using Deep Learning 🐟

## 📌 Project Overview
FishNet is a deep learning–based image classification project designed to accurately identify fish species from images.  
The project enhances **MobileNetV3Small** with a **lightweight self-attention mechanism** and **residual dense blocks** to achieve high accuracy while remaining computationally efficient.

This project was developed and trained using **Google Colab** and is suitable for **real-time, mobile, and edge-device deployment**.

---

## 🧠 Model Architecture
- **Backbone:** MobileNetV3Small (ImageNet pretrained)
- **Enhancements:**
  - Lightweight self-attention (GhostModule-inspired)
  - Residual Dense Block
  - Spatial Dropout
- **Optimizer:** Adam with Cosine Decay Learning Rate
- **Loss Function:** Categorical Cross-Entropy with Label Smoothing

---

## 📊 Dataset Details
- **Total Images:** 13,321
- **Number of Classes:** 31 fish species
- **Image Size:** 224 × 224
- **Split:**
  - Training: 67%
  - Validation: 20%
  - Testing: 13%

🔗 Dataset Source:  
https://www.kaggle.com/datasets/markdaniellampa/fish-dataset

---

## 🛠 Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas
- OpenCV
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## 📈 Performance
- **Test Accuracy:** 98.35%
- **Macro F1-Score:** 0.98
- **Top-2 Accuracy:** High consistency across all classes
- Outperformed models such as **ResNet50**, **InceptionV3**, **Xception**, and **DenseNet121**

---

## 📂 Outputs & Visualizations
The project generates:
- Accuracy vs Epoch plot
- Loss vs Epoch plot
- Confusion Matrix
- ROC Curves (multi-class)
- Random test image predictions
- Summary metrics (CSV)

All outputs are saved during runtime for analysis.


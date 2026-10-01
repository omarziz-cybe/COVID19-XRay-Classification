# 🫁 COVID-19 & Pneumonia Chest X-Ray Classification

An end-to-end Deep Learning pipeline built using PyTorch/TensorFlow to classify Chest X-Ray radiographs into COVID-19, Normal, and Viral Pneumonia cases with high sensitivity and precision.

---

## 📌 Overview
Early screening of COVID-19 and viral infections from medical imaging assists healthcare providers in rapid triage. This project implements Convolutional Neural Networks (CNNs) trained on chest radiography datasets, utilizing transfer learning, data augmentation, and regularization to achieve robust clinical diagnostic performance.

---

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

## ⚙️ Pipeline Highlights
- **Image Preprocessing**: CLAHE contrast enhancement, normalization, and resizing.
- **Data Augmentation**: Rotation, zooming, and horizontal flipping to prevent overfitting.
- **Architectures Evaluated**: Custom CNN architecture vs. Transfer Learning backbones.
- **Evaluation**: Confusion Matrix, ROC-AUC Curves, Precision, Recall, and F1-Score.

---

## 🚀 Quick Start
```bash
git clone [https://github.com/omarziz-cybe/COVID19-XRay-Classification.git](https://github.com/omarziz-cybe/COVID19-XRay-Classification.git)
cd COVID19-XRay-Classification
pip install -r requirements.txt
jupyter notebook

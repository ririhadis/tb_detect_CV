# Comparative Study of CNN and MobileNet for TB Detection from X-ray Images

This project focuses on detecting **Tuberculosis (TB)** from chest X-ray images using deep learning.  
Two approaches are compared:

- Custom Convolutional Neural Network (CNN)
- Transfer Learning using pre-trained **MobileNetV2**

The models are evaluated using **medical-relevant metrics** to ensure suitability for healthcare screening tasks.

---

## 📌 Project Objectives

- Build and compare CNN and transfer learning models for TB detection  
- Evaluate performance using clinical metrics:
  - Sensitivity (Recall)
  - Specificity
  - Positive Predictive Value (PPV)
  - Negative Predictive Value (NPV)
  - ROC-AUC
- Minimize **false negatives**, which is critical in medical screening systems

---

## 🧠 Models Implemented

### 1. Custom CNN
- Convolutional layers
- Max pooling layers
- Dropout for regularization
- Fully connected classification layers

### 2. MobileNetV2 (Transfer Learning)
- Pre-trained on ImageNet
- Global Average Pooling layer
- Fine-tuned classifier head

---

## 📊 Evaluation Metrics

The following metrics are used to assess model performance:

- Confusion Matrix
- Classification Report
- ROC Curve & AUC Score
- Sensitivity & Specificity
- PPV & NPV

These metrics provide better insight than accuracy alone for medical applications.

---

## 🗂 Dataset

- Dataset provided by **DataCamp**
- Used strictly for **educational purposes**
- Chest X-ray images labeled as:
  - TB Positive
  - TB Negative

---

## 🛠 Libraries & Tools Used

```python
PIL (Image)
NumPy
TensorFlow / Keras
scikit-learn
OpenCV
Matplotlib
IPython Widgets

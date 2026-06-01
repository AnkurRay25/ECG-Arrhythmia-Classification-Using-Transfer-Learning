# ECG Arrhythmia Classification Using Transfer Learning

## Overview

This project presents an automated ECG (Electrocardiogram) Arrhythmia Classification system using Deep Learning and Transfer Learning techniques. The objective is to accurately classify ECG images into different heart condition categories and support intelligent healthcare diagnostics.

The project evaluates the performance of multiple state-of-the-art transfer learning architectures, including DenseNet201, MobileNetV2, and ResNet50, for ECG image classification.

---

## Research Contribution

This project utilizes a publicly available ECG dataset developed and published by the author on Kaggle for heart condition classification and healthcare AI research.

---

## Dataset

### ECG Dataset for Heart Condition Classification

**Author:** Ankur Ray Chayan

**Citation:**

Ankur Ray Chayan. (2024). *ECG Dataset for Heart Condition Classification* [Dataset]. Kaggle.

DOI: https://doi.org/10.34740/KAGGLE/DS/5697968

### Dataset Features

* ECG Image Dataset
* Multiple Heart Condition Classes
* Medical Signal Classification
* Suitable for Deep Learning Applications
* Designed for Healthcare AI Research

### Dataset Link

https://doi.org/10.34740/KAGGLE/DS/5697968

---

## Project Objectives

* Develop an automated ECG classification system
* Compare multiple transfer learning architectures
* Improve classification accuracy through data augmentation
* Evaluate model performance using multiple metrics
* Support AI-assisted cardiac disease detection

---

## Technologies Used

### Programming Language

* Python

### Deep Learning Frameworks

* TensorFlow
* Keras

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* ImgAug
* OpenCV

---

## Methodology

### Data Preprocessing

* Image resizing
* Data cleaning
* Dataset balancing
* Data normalization

### Data Augmentation

Data augmentation techniques were applied to improve model generalization and reduce overfitting.

### Dataset Splitting

* Training Set
* Validation Set
* Testing Set

---

## Deep Learning Models

### MobileNetV2

A lightweight convolutional neural network optimized for efficient image classification.

**Accuracy:** 95.83%

### DenseNet201

A densely connected convolutional neural network that enables feature reuse and efficient gradient propagation.

**Accuracy:** 97.22%

### ResNet50

A residual neural network architecture designed to overcome vanishing gradient problems in deep networks.

**Accuracy:** 44.33%

---

## Model Performance Comparison

| Model       | Accuracy |
| ----------- | -------- |
| DenseNet201 | 97.22%   |
| MobileNetV2 | 95.83%   |
| ResNet50    | 44.33%   |

### Best Performing Model

 **DenseNet201**

Accuracy: **97.22%**

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Classification Report
* Confusion Matrix
* ROC Curve
* AUC Score

---

## Workflow

1. Dataset Collection
2. Data Preprocessing
3. Data Augmentation
4. Dataset Balancing
5. Train-Test Split
6. Transfer Learning Model Training
7. Model Evaluation
8. Performance Comparison

---

## Results

The experimental results demonstrate that transfer learning significantly improves ECG image classification performance.

Among the evaluated architectures, DenseNet201 achieved the highest accuracy of 97.22%, outperforming MobileNetV2 and ResNet50.

The findings indicate that DenseNet201 is highly effective for ECG-based heart condition classification and healthcare AI applications.

---

## Project Structure

```text
ecg-arrhythmia-classification/

│
├── ECG.ipynb
├── README.md
├── requirements.txt
│
├── images/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── model_comparison.png
│
└── dataset/
```

---

## Future Work

* Explainable AI (XAI) Integration
* Real-Time ECG Monitoring Systems
* Edge AI Deployment
* Mobile Healthcare Applications
* Hybrid CNN-LSTM Architectures
* Multi-Class Cardiac Disease Detection

---

## Applications

* Healthcare AI
* Medical Image Classification
* Cardiac Disease Detection
* Clinical Decision Support Systems
* Biomedical Signal Processing
* Deep Learning Research

---

## Author

### Ankur Ray Chayan

Machine Learning Researcher | Embedded Systems Researcher

GitHub:
https://github.com/AnkurRay25


---

## License

This project is licensed under the MIT License.



<div align="center">

# 🖼️ CIFAR-10 Image Classification using CNN with PyTorch

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge\&logo=python\&logoColor=white)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=for-the-badge\&logo=pytorch\&logoColor=white)](https://pytorch.org)
[![TorchVision](https://img.shields.io/badge/TorchVision-Computer%20Vision-orange?style=for-the-badge)](https://pytorch.org/vision/stable/index.html)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge\&logo=jupyter\&logoColor=white)](https://jupyter.org)
[![Dataset](https://img.shields.io/badge/Dataset-CIFAR--10-blue?style=for-the-badge)](https://www.cs.toronto.edu/~kriz/cifar.html)

> A Deep Learning image classification project built using Convolutional Neural Networks (CNNs) and PyTorch to classify images from the CIFAR-10 dataset into 10 different object categories.

</div>

---

# 🎯 Project Overview

This project demonstrates how to build and train a Convolutional Neural Network (CNN) using PyTorch for image classification.

The model learns visual patterns from thousands of labeled images and predicts the correct object category from ten different classes.

The CNN achieved an impressive **74.1% test accuracy** on the CIFAR-10 dataset.

The project covers the complete Deep Learning workflow:

* Dataset loading
* Data preprocessing
* CNN architecture design
* Model training
* Loss optimization
* Accuracy evaluation
* Image classification

---

# 📌 Problem Statement

Image classification is one of the most important tasks in Computer Vision.

The objective of this project is to train a CNN model capable of recognizing different objects from images and correctly assigning them to one of the CIFAR-10 categories.

The model learns hierarchical visual features such as edges, shapes, textures, and object structures using convolutional layers.

---

# 📊 Dataset Information

The project uses the **CIFAR-10 Dataset**, a widely used benchmark dataset for image classification.

### Dataset Statistics

| Property          | Value       |
| ----------------- | ----------- |
| Training Images   | 50,000      |
| Testing Images    | 10,000      |
| Image Size        | 32 × 32 RGB |
| Number of Classes | 10          |

---

# 🏷️ Classes

The model classifies images into the following categories:

* ✈️ Airplane
* 🚗 Automobile
* 🐦 Bird
* 🐱 Cat
* 🦌 Deer
* 🐶 Dog
* 🐸 Frog
* 🐴 Horse
* 🚢 Ship
* 🚚 Truck

---

# 🚀 Features

* CNN-based Image Classification
* Deep Learning using PyTorch
* Multi-Class Classification
* CIFAR-10 Dataset Training
* Convolutional Feature Extraction
* Max Pooling Layers
* Batch Training
* Accuracy Evaluation
* GPU Compatible Training
* Real-world Computer Vision Project

---

# 🧠 Deep Learning Pipeline

## Data Preparation

* Load CIFAR-10 Dataset
* Normalize Images
* Create DataLoaders
* Batch Processing

## Model Development

* Build CNN Architecture
* Apply Convolution Operations
* Feature Extraction
* Activation Functions
* Pooling Operations

## Training Process

* Forward Propagation
* Loss Calculation
* Backpropagation
* Weight Updates using Optimizer

## Evaluation

* Test Dataset Prediction
* Accuracy Calculation
* Performance Analysis

---

# 🏗️ CNN Architecture

```text
Input Image (32x32x3)

        ↓

Convolution Layer

        ↓

ReLU Activation

        ↓

Max Pooling

        ↓

Convolution Layer

        ↓

ReLU Activation

        ↓

Max Pooling

        ↓

Flatten Layer

        ↓

Fully Connected Layer

        ↓

Output Layer (10 Classes)
```

---

# ⚙️ Training Configuration

| Parameter     | Value                |
| ------------- | -------------------- |
| Framework     | PyTorch              |
| Dataset       | CIFAR-10             |
| Task          | Image Classification |
| Classes       | 10                   |
| Loss Function | CrossEntropyLoss     |
| Accuracy      | 74.1%                |

---

# 📈 Model Results

| Metric            | Score     |
| ----------------- | --------- |
| Test Accuracy     | **74.1%** |
| Number of Classes | 10        |
| Dataset           | CIFAR-10  |
| Framework         | PyTorch   |

The Convolutional Neural Network achieved **74.1% test accuracy** on the CIFAR-10 dataset.

The model successfully learned meaningful visual features and demonstrated strong image classification performance across ten different object categories.

---

# 📂 Project Structure

```text
CIFAR10-CNN-PyTorch/
│
├── CNN_for_CIFAR10.ipynb
├── data/
│   └── cifar-10-batches-py/
│       ├── data_batch_1
│       ├── data_batch_2
│       ├── data_batch_3
│       ├── data_batch_4
│       ├── data_batch_5
│       ├── test_batch
│       └── batches.meta
│
├── requirements.txt
└── README.md
```

---

# 🖥️ Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/harsh-v16/CIFAR10-CNN-PyTorch.git

cd CIFAR10-CNN-PyTorch
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Notebook

```bash
jupyter notebook CNN_for_CIFAR10.ipynb
```

---

# 📦 Dependencies

| Package     | Purpose                   |
| ----------- | ------------------------- |
| PyTorch     | Deep Learning Framework   |
| TorchVision | Computer Vision Utilities |
| NumPy       | Numerical Computing       |
| Matplotlib  | Visualization             |
| Jupyter     | Notebook Environment      |

---

# 🛠️ Tech Stack

| Tool             | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming Language    |
| PyTorch          | Deep Learning Framework |
| TorchVision      | Image Processing        |
| NumPy            | Numerical Computing     |
| Matplotlib       | Data Visualization      |
| Jupyter Notebook | Development Environment |
| GitHub           | Version Control         |

---

# 📚 Learning Outcomes

Through this project, I learned:

* Building Convolutional Neural Networks (CNNs)
* Image Classification using PyTorch
* Working with CIFAR-10 Dataset
* Data Loading and Preprocessing
* Feature Extraction using Convolution Layers
* Pooling Operations
* Multi-Class Classification
* Model Evaluation using Accuracy Metrics
* Deep Learning Workflow Implementation

---

# 🔮 Future Improvements

* Data Augmentation
* Batch Normalization
* Dropout Regularization
* Hyperparameter Tuning
* Transfer Learning with ResNet
* Streamlit Deployment
* Model Explainability Techniques

---

# 👤 Author

<div align="center">

**Harsh Chaudhary**

Computer Engineering Student | Machine Learning & Deep Learning Enthusiast

[![GitHub](https://img.shields.io/badge/GitHub-harsh--v16-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/harsh-v16)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Harsh%20Chaudhary-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/harsh-chaudhary-6ba5b8395/)

</div>

---

<div align="center">

⭐ If you found this project useful, consider giving it a star!

</div>

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

The CNN achieved **74.1% test accuracy** on the CIFAR-10 dataset.

The project covers the complete Deep Learning workflow:

* Dataset loading and preprocessing
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

The project uses the CIFAR-10 Dataset, a widely used benchmark dataset for image classification.

| Property          | Value       |
| ----------------- | ----------- |
| Training Images   | 50,000      |
| Testing Images    | 10,000      |
| Image Size        | 32 × 32 RGB |
| Number of Classes | 10          |

---

# 🏷️ Classes

The model classifies images into:

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
* Extract Visual Features
* Apply Activation Functions
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
Input Image (32×32×3)

        ↓

Conv2D (3 → 32, Kernel=3, Padding=1)

        ↓

ReLU Activation

        ↓

MaxPool2D (2×2)

        ↓

Conv2D (32 → 64, Kernel=3, Padding=1)

        ↓

ReLU Activation

        ↓

MaxPool2D (2×2)

        ↓

Conv2D (64 → 128, Kernel=3, Padding=1)

        ↓

ReLU Activation

        ↓

MaxPool2D (2×2)

        ↓

Flatten

        ↓

Linear (2048 → 256)

        ↓

ReLU Activation

        ↓

Linear (256 → 10)

        ↓

Output Classes
```

---

# ⚙️ Training Configuration

| Parameter     | Value                |
| ------------- | -------------------- |
| Framework     | PyTorch              |
| Dataset       | CIFAR-10             |
| Task          | Image Classification |
| Classes       | 10                   |
| Epochs        | 10                   |
| Loss Function | CrossEntropyLoss     |

---

# 📈 Model Results

| Metric            | Score     |
| ----------------- | --------- |
| Test Accuracy     | **74.1%** |
| Number of Classes | 10        |
| Dataset           | CIFAR-10  |
| Epochs            | 10        |

### Training Loss

| Epoch | Loss  |
| ----- | ----- |
| 1     | 0.756 |
| 2     | 0.632 |
| 3     | 0.529 |
| 4     | 0.428 |
| 5     | 0.347 |
| 6     | 0.279 |
| 7     | 0.212 |
| 8     | 0.172 |
| 9     | 0.135 |
| 10    | 0.113 |

The CNN achieved **74.1% test accuracy** while reducing training loss from **0.756 to 0.113** in only 10 epochs.

---

# 📂 Project Structure

```text
CNN-Based-Image-Recognition-using-PyTorch/
│
├── CNN_for_CIFAR10.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

---

# 🖥️ Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/harsh-v16/CNN-Based-Image-Recognition-using-PyTorch.git

cd CNN-Based-Image-Recognition-using-PyTorch
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
| Matplotlib  | Data Visualization        |
| Jupyter     | Notebook Environment      |

---

# 🛠️ Tech Stack

| Tool             | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming Language    |
| PyTorch          | Deep Learning Framework |
| TorchVision      | Image Processing        |
| NumPy            | Numerical Computing     |
| Matplotlib       | Visualization           |
| Jupyter Notebook | Development Environment |
| GitHub           | Version Control         |

---

# 📚 Learning Outcomes

Through this project, I learned:

* Understanding Convolution Filters
* Feature Maps and Kernels
* CNN Training using Backpropagation
* Image Feature Extraction
* Multi-Class Image Classification
* Working with CIFAR-10 Dataset
* Building Deep Learning Models using PyTorch
* CNN Architecture Design
* Loss Optimization and Model Evaluation
* Practical Computer Vision Fundamentals

---

# 🔮 Future Improvements

* Data Augmentation
* Batch Normalization
* Dropout Regularization
* Hyperparameter Tuning
* Transfer Learning using ResNet
* Streamlit Deployment
* Model Explainability

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

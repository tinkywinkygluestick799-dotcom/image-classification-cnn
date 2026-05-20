# Image Classification with CNNs

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange.svg)](https://tensorflow.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📌 Overview
This project compares **Convolutional Neural Networks (CNNs)** with traditional machine learning classifiers (Random Forest, SVM) on image classification tasks using the **MNIST** (digits) and **CIFAR-10** (objects) datasets.

## 📊 Results

| Model | MNIST Accuracy | CIFAR-10 Accuracy |
|-------|---------------|-------------------|
| Random Forest | 96.2% | 47.3% |
| SVM | 97.1% | 51.8% |
| CNN (Simple) | 98.9% | 72.4% |
| CNN (Deep) | 99.3% | 78.1% |

## 🛠️ Technologies
- Python 3.8+
- TensorFlow / Keras
- scikit-learn
- Matplotlib / Seaborn
- NumPy / Pandas

## 🚀 How to Run

```bash
git clone https://github.com/tinkywinkygluestick799-dotcom/image-classification-cnn
cd image-classification-cnn
pip install -r requirements.txt
python train_cnn.py

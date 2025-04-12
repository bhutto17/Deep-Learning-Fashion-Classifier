# 🧠 Fashion-MNIST Image Classification with CNN

A deep learning project for classifying grayscale fashion images using a Convolutional Neural Network (CNN). Built as part of the final project for the course *CSC 578: Deep Learning and Neural Networks* at DePaul University.

## 📁 Project Overview

This project applies a CNN to the Fashion-MNIST dataset to classify 28x28 grayscale images into 10 categories of clothing. The model was trained, evaluated, and documented in both a Jupyter notebook and a detailed final report written in LaTeX.

## 🔍 Problem Statement

Fashion-MNIST is a more challenging replacement for the original MNIST dataset. Many clothing items have overlapping visual features, making it difficult for traditional classifiers to differentiate between categories such as coats, shirts, and pullovers.

The goal was to:
- Build a simple yet effective CNN model
- Achieve high classification accuracy
- Understand common misclassifications and generalization performance

## 🧠 Model Architecture

The CNN used in this project includes:
- Two convolutional layers with ReLU activations
- Max-pooling layers for dimensionality reduction
- A fully connected dense layer with ReLU
- A final softmax layer for classification across 10 classes

Optimizer: `Adam`  
Loss Function: `Sparse Categorical Crossentropy`  
Final Accuracy Achieved: **90.73%** on the test set

## 📊 Dataset

- **Fashion-MNIST** by Zalando Research
- 60,000 training and 10,000 testing grayscale images
- 10 categories: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

## 📈 Results

- **Training Accuracy**: 95.54%  
- **Validation Accuracy**: 90.73%  
- **Test Accuracy**: 90.73%  
- Misclassifications were most common between visually similar items like shirts and coats or sandals and sneakers.

## 📎 Files Included

| File | Description |
|------|-------------|
| `Fashion_MNIST_CNN_Bhutto.ipynb` | Full Jupyter notebook with training, evaluation, and plots |
| `FProject_Report_Bhutto.pdf` | Formal LaTeX report (5 pages + appendix) |
| `model_summary.png`, `accuracy_loss_curves.png`, `misclassification_examples.png` | Visual outputs used in report & notebook |

## 🛠 Setup

To run this notebook locally:

```bash
pip install tensorflow matplotlib numpy

Then open

Fashion_MNIST_CNN_Bhutto.ipynb


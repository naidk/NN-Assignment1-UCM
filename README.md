# NN-Assignment1-UCM

# 🧠 CS5720 - Neural Networks and Deep Learning

## 📌 Home Assignment 1 – Summer 2025  
**University of Central Missouri**  
**Department of Computer Science & Cybersecurity**  
Instructor: Dr. I-Hua Tsai

---

## 👤 Student Info
- **Name:** Naidu Gudivada
- **Course:** CS5720 – Neural Networks and Deep Learning
- **Semester:** Summer 2025

---

## 📚 Assignment Overview

This assignment covers key concepts in TensorFlow for:

1. Tensor manipulation & reshaping
2. Loss function comparison
3. Neural network training with TensorBoard visualization
4. Answering analysis questions using experiment logs

---

## ✅ Tasks Completed

### 🔷 **1. Tensor Manipulations & Reshaping**
- Created a random tensor with shape `(4, 6)`
- Reshaped to `(2, 3, 4)` and transposed to `(3, 2, 4)`
- Demonstrated broadcasting from shape `(1, 4)` to `(3, 2, 4)`
- Explained broadcasting logic in TensorFlow

### 🔷 **2. Loss Functions & Hyperparameter Tuning**
- Computed Mean Squared Error and Categorical Cross-Entropy
- Compared loss values for different predictions
- Visualized using Matplotlib (bar chart)

### 🔷 **3. Neural Network Training + TensorBoard**
- Trained a basic neural network on the MNIST dataset
- Logged training and validation accuracy/loss to `logs/fit/`
- Visualized with TensorBoard: accuracy, loss, learning rate, histograms

### 🔷 **4. Analysis (Q&A)**
- All answers related to TensorBoard trends and overfitting are written directly inside the Colab notebook.

---

## 🚀 How to Run

1. Open the Colab notebook in your browser.
2. Run cells from top to bottom.
3. To launch TensorBoard:
   ```python
   %load_ext tensorboard
   %tensorboard --logdir logs/fit

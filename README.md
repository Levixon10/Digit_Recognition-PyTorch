# 🧠 Handwritten Digit Recognition with PyTorch (MNIST)

This project implements a **multiclass classification model** to recognize handwritten digits (0 to 9) using the **MNIST dataset**. Built using **PyTorch**, this simple feedforward neural network achieves high accuracy with minimal training.

---

## 📌 Features

- Trains on **MNIST dataset** of 28x28 grayscale digit images.
- Uses a **fully connected neural network** with one hidden layer.
- Implements **ReLU activation** and **CrossEntropyLoss**.
- Trains using the **Adam optimizer**.
- Achieves ~95% test accuracy in just 2 epochs.

---

## 🧰 Technologies Used

- Python 3.x
- PyTorch
- torchvision
- matplotlib
- numpy

---

## 📁 Dataset

The dataset is loaded using `torchvision.datasets.MNIST`:
- **60,000 training images**
- **10,000 test images**
- Each image: **28x28 pixels**, grayscale

---

## 🧠 Model Architecture

```text
Input Layer:       784 nodes (28x28 flattened)
Hidden Layer:      100 nodes
Activation:        ReLU
Output Layer:      10 nodes (digits 0–9)
Loss Function:     CrossEntropyLoss
Optimizer:         Adam
```
## 🙋 Author
Harsh Singh

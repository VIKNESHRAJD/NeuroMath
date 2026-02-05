# NeuroMath

# 📊 Activation Function Comparison using MNIST

## 🧠 Project Overview
This project compares the performance of different activation functions in a neural network using the MNIST handwritten digit classification dataset. The goal is to analyze how activation functions affect training performance, accuracy, and learning stability.

---

## 📚 Dataset – MNIST

MNIST is a benchmark dataset containing grayscale images of handwritten digits (0–9).

### Dataset Details
- Total Images: 70,000
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Number of Classes: 10

---

## ⚙️ Data Preprocessing

### ✅ Normalization
Pixel values are scaled from **[0, 255] → [0, 1]** to improve model performance and training stability.

```python
x_train = x_train / 255.0
x_test = x_test / 255.0

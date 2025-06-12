# Handwritten Digit Recognition (MNIST)

This project demonstrates the recognition of handwritten digits using deep learning. It compares two neural network architectures: an Artificial Neural Network (ANN) and a Convolutional Neural Network (CNN), using the MNIST dataset.

---

## 📂 Project Structure

- `digit_recognition.py`: Main Python file containing all the code — data loading, preprocessing, model training, evaluation, and predictions.

---

## 🧠 Models Used

### 1. Artificial Neural Network (ANN)
- **Input Layer:** Flattened 28x28 image
- **Hidden Layers:** Dense (128, ReLU), Dense (64, ReLU)
- **Output Layer:** Dense (10, Softmax)

### 2. Convolutional Neural Network (CNN)
- **Conv Layer:** 32 filters, 3x3 kernel, ReLU
- **Pooling Layer:** MaxPooling 2x2
- **Flatten + Dense Layers:** Dense (128, ReLU), Dense (10, Softmax)

---

## 📊 Dataset

- **Source:** [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- **Samples:** 60,000 training images, 10,000 testing images
- **Shape:** 28x28 grayscale images of handwritten digits (0–9)

---

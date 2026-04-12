# 🧠 Artificial Neural Network from Scratch (MNIST Digit Recognition)

## 📌 Overview

This project implements a **fully connected Artificial Neural Network (ANN)** from scratch using **NumPy**, without relying on high-level deep learning frameworks.

The model is trained on the **MNIST dataset** to classify handwritten digits (0–9), demonstrating core neural network concepts through practical implementation.

---

## 🎯 Objectives

* Understand the internal working of neural networks
* Implement forward and backward propagation manually
* Train a model on real-world data
* Evaluate model performance using accuracy

---

## 🏗️ Model Architecture

* **Input Layer:** 784 neurons (28×28 pixels)
* **Hidden Layer:** 128 neurons (ReLU activation)
* **Output Layer:** 10 neurons (Softmax activation)

---

## ⚙️ Features Implemented

* ✅ Weight & bias initialization
* ✅ Forward propagation
* ✅ ReLU activation function
* ✅ Softmax output layer
* ✅ Cross-entropy loss
* ✅ Backpropagation (manual implementation)
* ✅ Gradient descent optimization
* ✅ Accuracy evaluation

---

## 📂 Project Structure

```
ann-mnist-project/
│── ann.py              # Main implementation
│── README.md           # Project documentation
│── requirements.txt    # Dependencies
```

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**

  * NumPy
  * Matplotlib
  * TensorFlow (only for dataset loading)

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/Sanikakalyani/mnist-digit-classification-ann.git
cd ann-mnist-from-scratch
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python ann.py
```

---

## 📊 Results

* Training Accuracy: **~85–90%** (on subset of dataset)
* Loss decreases steadily during training
* Model successfully predicts handwritten digits

---

## 📷 Sample Output

* Displays handwritten digit image
* Shows predicted vs actual label

---

## 🧠 Key Learning Outcomes

* Gained hands-on understanding of ANN internals
* Learned how backpropagation updates weights
* Understood importance of activation functions
* Experienced training on real dataset

---

## 🚀 Future Improvements

* Implement mini-batch gradient descent
* Add multiple hidden layers
* Improve accuracy with hyperparameter tuning
* Compare performance with TensorFlow/PyTorch models

---


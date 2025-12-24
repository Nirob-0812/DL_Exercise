# Deep Learning Exercises 🧠

This repository contains a collection of fundamental **Deep Learning** concepts and implementations using **TensorFlow/Keras**. It serves as a practical guide to understanding neural networks, evaluation metrics, and mathematical functions used in modern AI.

## 📂 Repository Structure

The projects are organized into specific directories, each focusing on a core concept:

```text
DL_Exercise/
├── Activation_Function/       # Visualization & math of Sigmoid, ReLU, Tanh, etc.
├── Hand_Digit_Classification/ # Neural Network for MNIST digit recognition
├── Metrics_basic/             # Implementation of loss functions & accuracy metrics
└── main.py                    # Entry point for testing scripts

```

## 🛠️ Tech Stack

* **Language**: Python 3.x
* **Libraries**:
* `tensorflow` / `keras` - Building and training neural networks.
* `numpy` - Matrix operations and mathematical calculations.
* `matplotlib` - Plotting accuracy curves and activation functions.



## 📘 Module Breakdown

### 1. Hand Digit Classification

A complete pipeline to recognize handwritten digits (0-9) using the **MNIST dataset**.

* **Features**: Data preprocessing, model architecture design, training loops, and evaluation.
* **Goal**: Achieve high accuracy on test data using dense or convolutional layers.

### 2. Activation Functions

A study of the mathematical functions that introduce non-linearity to neural networks.

* **Implemented Functions**: Sigmoid, ReLU, Leaky ReLU, Tanh, Softmax.
* **Visualization**: Plots demonstrating the output range and derivative behavior of each function.

### 3. Metrics Basic

Implementation of core evaluation metrics to assess model performance.

* **Metrics Covered**: Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
* **Loss Functions**: Mean Squared Error (MSE), Cross-Entropy Loss.

## 🚀 Installation & Usage

1. **Clone the repository:**
```bash
git clone [https://github.com/Nirob-0812/DL_Exercise.git](https://github.com/Nirob-0812/DL_Exercise.git)

```


2. **Navigate to the directory:**
```bash
cd DL_Exercise

```


3. **Install Dependencies:**
```bash
pip install tensorflow numpy matplotlib

```


4. **Run a Project:**
Navigate to a subfolder (e.g., `Hand_Digit_Classification`) and run the notebook or script:
```bash
cd Hand_Digit_Classification
jupyter notebook

```



## 📜 Credits

* **Author**: Nirob
* **Tools**: Python, TensorFlow, Jupyter Notebooks.

---

*This repository is for educational purposes and reference.*

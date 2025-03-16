
# Neural Network Optimization on MNIST

This repository implements a multi-layer perceptron from scratch for handwritten digit recognition on the MNIST dataset. The network is designed for binary classification (even vs. odd) and compares three optimization algorithms:

- **Gradient Descent (GD):** 81.25% accuracy
- **SGD with Momentum:** 87.13% accuracy
- **Adam Optimizer:** 96.82% accuracy

## Project Overview

- **Implementation:**  
  Developed in Python using NumPy. Includes forward propagation, backpropagation, and custom implementations of ReLU, sigmoid, and binary cross-entropy loss.

- **Data Preprocessing:**  
  Normalization of pixel values, flattening images, and appending a bias term.

- **Weight Initialization:**  
  Utilized Xavier initialization for stable convergence.


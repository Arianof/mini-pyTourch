# Mini PyTorch

Mini PyTorch is a lightweight, educational deep learning framework built from scratch. The project aims to demystify the inner workings of modern automatic differentiation and neural network training by implementing key components of a deep learning framework, inspired by PyTorch.

## Overview

This project provides:
- **A Custom Tensor Class:**  
  Implements basic arithmetic operations while building a dynamic computation graph. Each `Tensor` stores its data, gradient, and the operation that created it, enabling automatic differentiation via backpropagation.

- **Autograd Engine:**  
  Automatically computes gradients through a topologically sorted backward pass. Each operation defines its own backward function to correctly propagate gradients through the computation graph.

- **Activation Functions:**  
  Includes non-linear functions such as the hyperbolic tangent (`tanh`), which are crucial for building complex neural network models.

- **Neural Network Modules:**  
  - **Neuron:** A single computational unit that performs a weighted sum of inputs, adds a bias, and applies an activation function.
  - **Layer:** A collection of neurons that together form a fully connected (dense) layer.
  - **MLP (Multi-Layer Perceptron):** A stack of layers, forming a complete neural network model.

- **Optimizer:**  
  A basic gradient descent optimizer that updates the model's parameters by subtracting the gradient scaled by a learning rate.

- **Loss Function:**  
  Implements the Mean Squared Error (MSE) loss to quantify the difference between the model's predictions and the true values.

- **Prediction Function:**  
  A simple interface to generate predictions from the model for a given dataset.

## Purpose

This mini PyTorch project is designed as a learning tool for understanding:
- How computation graphs are built and visualized.
- The mechanics of automatic differentiation and backpropagation.
- The structure of neural networks and how layers and neurons interact.
- The fundamentals of training a model using gradient descent.

## Getting Started

To start experimenting with Mini PyTorch, simply clone the repository, explore the code, and try building and training your own neural network models. Contributions and feedback are welcome!



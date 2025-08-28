# Digit Recognizer Project

This project implements a simple feedforward neural network from scratch using NumPy only, to recognize handwritten digits from the MNIST dataset. The model is trained using a single hidden layer and is capable of achieving around 85% accuracy on both training and development datasets.

## Features

- Pure NumPy implementation (no deep learning libraries)
- One hidden layer with ReLU activation
- Softmax output layer for classification
- Manual implementation of forward and backward propagation
- Handwritten digit prediction and visualization
- Achieves ~85% accuracy on SIMPLE MNIST training and dev sets

## Dataset

The project uses the MNIST digit recognition dataset provided in CSV format, where each row represents a 28x28 grayscale image of a digit (flattened into 784 values), with the first column being the digit label.

## Future Work

To further enhance the model's performance, I plan to implement advanced optimizers like Adam, which can accelerate training and potentially improve accuracy by adapting the learning rate. Additionally, incorporating techniques like dropout layers could help reduce overfitting, leading to a more efficient and generalized model. These improvements could boost the model’s overall robustness and prediction accuracy.

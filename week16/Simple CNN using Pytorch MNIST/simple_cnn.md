# Simple CNN for MNIST - Mini Project Summary

In this mini-project, I built and trained a simple Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. 

---

## Architecture Overview

The CNN model consists of two convolutional layers followed by a fully connected layer. The architecture is designed for simplicity and fast training on MNIST's 28x28 grayscale images.

### Layer-wise Breakdown:

| Layer Type       | Configuration                             | Output Shape (for 28x28 input) |
|------------------|-------------------------------------------|---------------------------------|
| Conv2d           | in_channels=1, out_channels=8, kernel=3x3 | 28x28                           |
| ReLU             | Activation                                 | 28x28                           |
| MaxPool2d        | kernel=2x2                                 | 14x14                           |
| Conv2d           | in_channels=8, out_channels=16, kernel=3x3| 14x14                           |
| ReLU             | Activation                                 | 14x14                           |
| MaxPool2d        | kernel=2x2                                 | 7x7                             |
| Flatten          | -                                          | 784                             |
| Linear (FC)      | in_features=784, out_features=10           | 10                              |

---


## Training Configuration

| Parameter        | Value        |
|------------------|--------------|
| Epochs           | 3            |
| Batch Size       | 64           |
| Learning Rate    | 0.0003       |
| Optimizer        | Adam         |
| Loss Function    | CrossEntropy |

---

## Results

| Dataset       | Accuracy (%)   |
|---------------|----------------|
| Training Set  | **96.58**      |
| Test Set      | **97.00**      |

The model generalized well, showing minimal overfitting and strong classification accuracy even with a shallow architecture and only 3 epochs of training.

---


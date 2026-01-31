Digit Classification using Neural Network (NumPy Only)
Overview

This project implements a fully connected neural network from scratch using NumPy to classify handwritten digits from the MNIST dataset.
No deep learning frameworks such as TensorFlow or PyTorch are used for model training or inference.

The project demonstrates a clear understanding of neural network fundamentals, including forward propagation, backpropagation, activation functions, and optimization.


Features

Neural network implemented entirely using NumPy

ReLU and Softmax activation functions

Categorical Cross-Entropy loss

Mini-batch Gradient Descent

Training and accuracy visualization

MNIST handwritten digit classification



Training Details

Dataset: MNIST

Loss Function: Categorical Cross-Entropy

Optimizer: Mini-batch Gradient Descent

Learning Rate: 0.01

Batch Size: 128

Epochs: 50

Weight Initialization: He Initialization


Results

Training Accuracy: ~97%

Test Accuracy: ~96%

The model converges stably after tuning the learning rate and applying proper weight initialization.


Technologies Used

Python

NumPy

Matplotlib

Note: Keras is used only for loading the MNIST dataset.
The neural network implementation is completely NumPy-based.


Key Learnings

Neural network implementation from scratch

Backpropagation without ML libraries

Importance of learning rate and initialization

Practical experience with NumPy-based ML


Future Improvements

Add multiple hidden layers

Implement Adam optimizer from scratch

Add confusion matrix visualization

Pure NumPy dataset loading

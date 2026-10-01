# Digit recognition with PyTorch (MNIST)
A simple fully-connected neural network built with PyTorch that classifies handwritten digits (0-9) from the MNIST dataset.

## Accuracy
Around **97-98%** on the 10,000 test images (after 2 epochs)

## Model Architecture 
- Input: 784 neurons (28*28 pixels)
- Hidden Layer: 500 neurons + ReLU
- Output: 10 neurons
- Loss: CrossEntropyLoss
- Optimizer: Adam

## What I Learned
- Loading and preprocessing the MNIST dataset
- Building a feed forward neural network with 'nn.Module'
- Writing training and evaluation loops
  

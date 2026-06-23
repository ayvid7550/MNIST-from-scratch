# MNIST Digit Classifier — From Scratch

2-layer MLP trained on MNIST, implemented in NumPy with no ML frameworks.

## Architecture
- Input: 784 (28x28 flattened)
- Hidden: 128 neurons, ReLU activation
- Output: 10 neurons, Softmax activation

## What's implemented
- Forward pass
- Cross-entropy loss
- Backpropagation (derived manually)
- Gradient descent

## Result
~95% accuracy on validation set (10,000 examples)

## Dataset
MNIST via Kaggle: https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

## PyTorch Port
Same 784 -> 128 -> 10 architecture, reimplemented in PyTorch using nn.Module, DataLoader, and CrossEntropyLoss. Achieved ~97% test accuracy in 5 epochs.

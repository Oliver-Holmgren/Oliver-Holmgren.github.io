# Fully Connected Neural Network (Adam) — MNIST

This project implements a **fully connected neural network from scratch in NumPy** and trains it on the **MNIST digit classification** task using the **Adam optimizer**. The notebook includes the full training loop (forward pass, backpropagation, parameter updates) and plots training/test cost and accuracy over time.

## Contents
- `ADAM-Network.ipynb` — pre-run notebook with training results and curves

## Highlights
- Multi-layer perceptron with ReLU hidden layers
- Softmax + cross-entropy loss
- Mini-batch training
- Adam optimization (bias-corrected moment estimates)

## Data
Expects the MNIST data arranged in `MNIST/Train/` and `MNIST/Test/` with one folder per label (`0–9`).

## Results
See the notebook outputs for training curves, final accuracy, and runtime.

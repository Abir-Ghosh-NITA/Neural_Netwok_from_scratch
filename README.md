# Neural_Netwok_from_scratch
Neural network implemented from scratch in NumPy to compare SGD, Momentum, and Adam optimizers on MNIST, with full backpropagation, mini-batch training, and convergence analysis.
📘 Comparative Study of Optimization Algorithms in Neural Network Training
🔎 Overview
This project implements a two-layer neural network from scratch using NumPy and performs a comparative study of three widely used optimization algorithms:
Stochastic Gradient Descent (SGD)
Momentum
Adam
The network is trained on the MNIST handwritten digit dataset to analyze optimizer behavior in terms of convergence speed, stability, and generalization performance.
Unlike framework-based implementations, this project manually derives and implements:
Forward propagation
Backpropagation
Mini-batch gradient descent
He weight initialization
Cross-entropy loss
The goal is to deeply understand gradient-based optimization dynamics.
🎯 Objectives
Implement neural network training without deep learning libraries
Derive and code backpropagation manually
Compare optimizer performance experimentally
Analyze convergence characteristics
Study training vs test accuracy behavior
🧠 Model Architecture
Input Layer: 784 neurons (28×28 MNIST images flattened)
Hidden Layer: 128 neurons (ReLU activation)
Output Layer: 10 neurons (Softmax activation)

Initialization: He Initialization
Loss Function: Cross-Entropy Loss
Training Strategy: Mini-Batch Gradient Descent

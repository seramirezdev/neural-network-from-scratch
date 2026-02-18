# Neural Network from Scratch

A complete implementation of a neural network using only NumPy — no deep learning frameworks. The notebook walks through building each component step by step, from a single neuron to a full training loop.

## Topics Covered

- **Single neuron to layers**: manual computation, then vectorized with matrix multiplication
- **Forward pass**: inputs through multiple dense layers
- **Activation functions**: ReLU, Softmax
- **Loss function**: Categorical Cross-Entropy (combined with Softmax for numerical stability)
- **Backpropagation**: computing gradients for weights, biases, and activations
- **Optimizers**: Gradient Descent, SGD (with decay and momentum), Adagrad, RMSProp, Adam
- **Regularization**: L1 and L2 (weights and biases), Dropout
- **Hyperparameter tuning**: train/validation/test splits, k-fold cross-validation

## Requirements

- Python 3
- NumPy

# Neural Net Project

## Overview

This project demonstrates a simple neural network implemented **from scratch** using Python and NumPy, without relying on deep learning frameworks. The network is trained on the `moonDataset.csv` dataset, which contains 201 records with three features each. The goal is to perform binary classification by manually applying forward and backward propagation over 20 epochs.

## Features

- Implements sigmoid and tanh activation functions along with their derivatives.
- Uses mean squared error as the loss function.
- Updates weights and biases manually using gradient descent.
- Visualizes training error over epochs with Matplotlib.

## Dataset

The dataset `moonDataset.csv` should be placed in the same directory as the script. It contains 3 feature columns and 1 target label column.

## How to Run

1. Make sure you have Python 3.x installed on your system.
2. Install the required libraries by running:

```bash
pip install numpy pandas matplotlib
```
## License
This project is licensed under the MIT License — see the LICENSE file for details.

## Acknowledgments
This project is created for educational purposes to understand the fundamentals of neural networks and backpropagation by building them from scratch without using external deep learning libraries.

# Deep Learning Optimization Algorithms

This repository contains Python implementations of two fundamental optimization algorithms used in deep learning: Gradient Descent (GD) and Stochastic Gradient Descent (SGD).

## Gradient Descent (GD)

Gradient descent is a widely used optimization algorithm for minimizing loss functions in deep learning models. It iteratively adjusts the parameters of the model to minimize the loss.

### Description
Gradient Descent follows these steps:
1. **Initialization**: Start with an initial guess for the parameters.
2. **Compute Gradient**: Calculate the gradient of the loss function with respect to the parameters.
3. **Update Parameters**: Adjust the parameters in the opposite direction of the gradient to minimize the loss.
4. **Repeat**: Iterate steps 2 and 3 until convergence.

## Stochastic Gradient Descent (SGD)

Stochastic gradient descent is a variant of gradient descent that updates the parameters using a random subset of the training data at each iteration. It helps to speed up the convergence process, especially for large datasets.

### Description
Stochastic Gradient Descent follows these steps:
1. **Initialization**: Start with an initial guess for the parameters.
2. **Random Data Selection**: Choose a random subset of the training data.
3. **Compute Gradient**: Calculate the gradient of the loss function using the selected data.
4. **Update Parameters**: Adjust the parameters based on the computed gradient.
5. **Repeat**: Iterate steps 2-4 until convergence.

## Usage

You can use the provided implementations of GD and SGD to optimize the parameters of your deep learning models. Simply integrate the algorithms into your training pipeline to minimize the loss function during model training.

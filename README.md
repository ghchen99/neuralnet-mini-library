# Neural Network Mini-Library

This mini-library provides a low-level implementation of a multi-layered neural network, including a basic implementation of the backpropagation algorithm. It allows you to create and train neural networks for various tasks.

## Requirements
- Python 3.x
- NumPy

## Usage
## Linear Layer
The LinearLayer class implements a linear layer that performs an affine transformation XW + B on a batch of inputs X. It includes methods for forward pass, backward pass, and parameter update.

## Activation Functions
The mini-library provides two activation function classes: SigmoidLayer and ReluLayer. These classes implement the forward and backward pass methods for the respective activation functions.

## Multi-Layer Network
The MultiLayerNetwork class represents a multi-layer network consisting of stacked linear layers and activation functions. It includes methods for forward pass, backward pass, and parameter update.

## Trainer
The Trainer class handles data shuffling, training a given network using minibatch gradient descent on a training dataset, and computing the loss on a validation dataset.

## Preprocessor
The Preprocessor class performs min-max scaling on the data, scaling it to the interval [0, 1].

## Dataset
A simple dataset is provided for debugging purposes. You can find the dataset at https://en.wikipedia.org/wiki/Iris_flower_data_set in the file iris.dat.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

# Neural Network Training Code README
## Overview
This Python code is a simple implementation of a feedforward neural network with two hidden layers. It is designed for training the neural network using a backpropagation algorithm. The code takes input values for x1 and x2, and it tries to adjust the network's weights to make the output as close as possible to a given target value.

## Getting Started
### Prerequisites:

Python: Make sure you have Python installed on your system. This code was developed using Python 3.

NumPy: This code uses the NumPy library for numerical operations. You can install it using pip:

`pip install numpy`

### Running the Code:

To run the code, follow these steps:

Save the code to a Python file (e.g., neural_network.py).

Open your terminal or command prompt.

Navigate to the directory where the code is located.

Run the code using Python:

`python neural_network.py`

You will be prompted to enter values for x1, x2, and the target value. The neural network will attempt to adjust its weights to make the output close to the target value.

## Code Structure
sigmoid Function:

The sigmoid function implements the sigmoid activation function, which is used in the neural network to introduce non-linearity.

propagate Function:

This is the main function of the code, responsible for training the neural network.
It defines the neural network architecture with two hidden layers and an output layer.
It performs forward and backward passes for a specified number of iterations.
During the forward pass, it calculates the output of each layer.
During the backward pass, it updates the weights based on the calculated errors.

## Output
The code will provide detailed output during each iteration of the training process. It will display the forward pass and backward pass results, including the network's predictions, errors, and weight updates.

The training process will continue until the error is less than 0.01 or the specified number of iterations is reached.

## Configuration
You can adjust the network architecture, learning rate, and the number of iterations by modifying the variables within the propagate function.

Example Usage
Here's an example of how to use the code:

`python neural_network.py`

You will be prompted to enter the values for x1, x2, and the target value, and the code will demonstrate the training process.

## License
This code is provided under an open-source license. See the LICENSE file for details.

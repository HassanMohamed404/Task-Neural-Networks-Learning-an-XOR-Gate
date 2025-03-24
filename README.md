# Logic Gates Neural Network

## Overview
This project implements a simple neural network to learn and simulate basic logic gates (AND, OR, NAND, XOR) using TensorFlow. The XOR gate is implemented using a two-layer neural network, as it is not linearly separable.

## Features
- Implements AND, OR, NAND, and XOR logic gates
- Uses TensorFlow for training the neural networks
- Includes a fully connected neural network for learning the XOR function
- Uses gradient descent optimization for training
- Computes accuracy and loss during training

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install numpy tensorflow
```

## Usage
Run the script to train the neural networks and test their predictions:

```bash
python logic_gates_nn.py
```

### Expected Output
After training, the model should output predictions for the XOR gate, showing correct logical outputs:

```plaintext
XOR Gate Predictions:
Input: [0, 0], Output: [0]
Input: [0, 1], Output: [1]
Input: [1, 0], Output: [1]
Input: [1, 1], Output: [0]
```

## How It Works
1. The `LogicGate` class represents a simple perceptron model.
2. The `XORGate` class uses a two-layer neural network with a hidden layer to model the XOR function.
3. The training function updates weights using gradient descent to minimize error.
4. The trained model is used to predict outputs for logic gate inputs.

## Improvements & Future Work
- Implement additional logic functions (e.g., XNOR)
- Optimize training parameters for faster convergence
- Use a more advanced optimizer like Adam for better performance

## Author
Developed by **Hassan Mohamed**

## License
This project is open-source and available under the MIT License.


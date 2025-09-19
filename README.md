🧠 MLP from Scratch with NumPy

This repository contains two educational examples of building a Multilayer Perceptron (MLP) from scratch using only NumPy.
Both examples are designed to be easy to read and fully transparent, perfect for learning and explaining how neural networks work under the hood.

📌 Examples Included
1️⃣ XOR Problem

A classic test case for neural networks, showing that an MLP can solve problems that are not linearly separable.

Architecture:

2 input neurons

1 hidden layer with 2 neurons

1 output neuron

Training Details:

Sigmoid activation

Mean Squared Error (MSE) loss

Manual backpropagation with gradient descent

✅ Goal: Predict the correct XOR output (0 or 1) given two binary inputs.

2️⃣ Binary Pixel Matrix Mapping

A slightly bigger example where the network learns to reproduce binary matrices (0s and 1s), similar to tiny black-and-white images.

Architecture:

3 input neurons

3 hidden neurons

3 output neurons

Training Details:

Sigmoid activation

Mean Squared Error (MSE) loss

Manual backpropagation with gradient descent

✅ Goal: Learn the identity function — output should match the input matrix, making it easier to visualize how the network propagates information.

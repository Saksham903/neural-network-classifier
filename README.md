# neural-network-classifier

This project is part of my Module 11 assignment where I built a simple neural network from scratch using only NumPy — without using TensorFlow or PyTorch.
The goal of this project is to understand the internal working of a neural network like feedforward, backpropagation, activation functions, and weight updates.

# Project Overview
In this project, I created a small neural network that can recognize the characters A, B, and C using simple 5×6 pixel patterns.
Each character is represented as binary pixel data (0s and 1s), and the neural network learns to classify which letter it is.

# The model:

# Takes 30 input neurons (for 5×6 images)

Has one hidden layer

# Uses sigmoid activation function

# Trains using custom backpropagation

# Predicts which letter (A, B, or C) the input image represents.

# Technologies Used:- Python 3, NumPy, Matplotlib


# Now Iam explaing the appraoches that i have used 

Firstly i have created the pixels for the A,B, and C.
Flatten them into 1D arrays and use them as a training data.
Initialize random weights and biases.
Performed the forward propogation  to calculate the output of the model.
Used the backward propogation to update the weights and reduce the error.
Plot the loss and accuracy  over multiple epochs.
Finally test the model with passing the input values and visualize the results of the input you are entering.


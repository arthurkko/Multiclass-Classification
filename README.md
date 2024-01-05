# Multiclass Classification

This work aims to develop a neural network using the TensorFlow-Keras platform to perform a multi-class classification task.

The classification task in this work involves identifying hand signals from images.

To achieve this, two types of artificial neural networks will be used: dense and convolutional.

## Problem Definition:

The objective of this problem is to develop an ANN that takes an image of hand signals as input and assesses the probability of the hand's fingers showing a number from 0 to 5. It determines the most likely number among the six possibilities.

The database used in this work is SIGNS, consisting of hand signal images created by Andre Ng (deeplearning.ai). This database can be obtained at the following link: https://github.com/cs230-stanford/cs230-code-examples/tree/master/tensorflow/vision

The database contains 1080 training examples and 120 test examples. Each example consists of a colored image associated with a label of 6 classes. The figure below shows some examples of these images.

![](img/SIGNS.png)

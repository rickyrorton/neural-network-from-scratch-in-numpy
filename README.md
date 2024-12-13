# Artificial Neural Network using numpy
This is a neural network made completely using Numpy without the help of ML/DL Libraries like Tensorflow/PyTorch

The ANN is used to classify the MNIST Handwritten digits dataset.

## Model Description

The model consists of an input layer, hidden layer and ouput layer of interconnected neurons.

* Input layer takes an image of shape 28x28 (784 pixels).
* Hidden layer has 10 neurons with 784 weighted inputs(connected to input layer) and a bias each.
* Output layer has 10 neurons with 10 weighted inputs(connected to hidden layer) and a bias each.

## Code Description

Code consists of user defined functions for the following

* Forward Propagation
* Backward Propagation
* ReLU (and its derivative)
* Softmax
* Gradient Descent

## Results 

For a learning rate of 0.3 and 501 epochs the confusion matrix obtained is shown below:

![image](https://github.com/user-attachments/assets/f2ce55f9-07de-445f-847b-eea399c369ab)

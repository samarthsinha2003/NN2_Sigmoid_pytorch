# NN2_beginner_Sigmoid_pytorch
Beginner level Neural Network utilizing Sigmoid activation function

The neural network consists of an input layer, a hidden layer with sigmoid activation function, 
and an output layer with sigmoid activation function. The input and output layers have 2 and 1 neurons 
respectively, and the hidden layer has 3 neurons.

The model is trained using stochastic gradient descent (SGD) optimizer and binary cross-entropy loss. 
The input data (X) and corresponding output data (y) are defined and used to train the model for 1000 epochs.

After training, the model is tested on the same input data, and the predicted output is compared to the actual output.

The sigmoid activation function maps any input to the range of (0, 1).
It's commonly used in binary classification problems, where the output 
of the neural network should be either 0 or 1.

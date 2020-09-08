# mnist

MNIST Digit Classification using an ANN, k-Nearest Neighbour and hybrid of the two.

## Setup

[Task 1](https://github.com/oaarnikoivu/mnist/blob/master/Task1.ipynb) and [Task 2](https://github.com/oaarnikoivu/mnist/blob/master/Task2.ipynb) evaluates the behaviour of different hyperparameters on the performance of the Artificial Neural Network (ANN) and k-NN (K-Nearest Neighbours). For both the ANN and k-NN, training is done using 1500 samples and tested on 10000 examples. The results demonstrate that 50 epochs, 0.3 learning rate, 1 batch size and 200 hidden nodes resulted in optimal performance for the ANN, whereas for the k-NN the best results were obtained using weighted voting with k being equal to 3.

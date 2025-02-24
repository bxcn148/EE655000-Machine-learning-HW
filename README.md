Download link :https://programming.engineering/product/ee655000-machine-learning-hw3/


# EE655000-Machine-learning-HW
EE655000 Machine learning HW
Part1. Handwriting homework assignment

You can find the corresponding problems from the textbook.

(25 points) Exercise 5.6

(25 points) Exercise 5.24

(25 points) Exercise 6.16

(25 points) Exercise 6.26


Part2. Computer assignment

In this problem, you need to build a neural network in order to classify images into three classes. Particularly, you need to code on the feedforward network structure and error backpropagation algorithm by yourself in order to realize the learning process, instead of using related functions in Python that do the tricks for you.


Fig. 1: Illustration of the data set containing images of three kinds of fruits. Your task is to establish and train a neural network model capable of performing classification.

Data

Data, encapsulated in Data.zip, in this problem are the images of three fruits as shown in Fig. 1, which are respectively deposited in the three folders Carambola, Lychee, and Pear under two folders for training and testing. In the data for training, each class has 490 images, you can partition this data by yourself to form the validation set.


Figure 2: Two layers neural network with three inputs nodes and three output nodes.

Problem Description

Please build a two-layer (as in Fig. 2) neural network to perform the classification to the images in the given data set. More detailed steps are as follows:

The very first step is to perform dimensionality reduction using principal component analysis (PCA). This practical pre-processing technic was introduced in Sec. 12.1 from the PRML textbook, you can read it to understanding what PCA is all about.

Then, please employ PCA to map the images in the data down to 2 dimensions, i.e. extract the coefficients of the two principle components for the given data set. You don’t need to write PCA by yourself; instead, you can use any functions, in Python, about PCA.

Build a two-layer neural network. The number of hidden units has to be decided by you. Please adopt sigmoid function as the nonlinear mapping in the hidden neurons, and train the weights using stochastic gradient descent. You need to implement the backpropagation algorithm in your code to evaluate the gradient.

Note that the number of input nodes in the neural network here is three, corresponding to the two principal components and the bias.

In the 2nd part, please build a three-layer neural network to perform the classification to the images in the given data set. Also show the decision regions and discuss the performance or decision boundary behavior difference from that in part (a) by adding one more layer here.


Report (100 points)

For both two-layer and three-layer neural network

(35 points) Describe your model architecture details and PCA method.

(10 points) Show your test accuracy.

(10 points) Plot training loss curves.

(45 points) Plot decision regions and discuss the training / testing performance with different settings designed by yourself.

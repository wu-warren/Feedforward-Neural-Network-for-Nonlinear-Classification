# Feedforward-Neural-Network-for-Nonlinear-Classification

In this report, I will examine the efficacy of shallow neural networks with different numbers of neurons at
a binary classification task where the classes are separated by a nonlinear decision boundary, specifically
the parabola X2 = X2
1 (equivalent to y = X2).
The idea for this project came from the Math 118 class, where my professor discussed the short-
comings of logistic regression at separating classes where the decision boundary is nonlinear, and that
neural networks can perform this task more effectively. We also discussed the Universal Approximation
Theorem1, which demonstrates that any continuous function can be approximated by a feedforward
neural network with one hidden layer and a sufficient number of neurons. It does not, however, say
what this number of neurons is for a given function. I decided to take this idea further and examine
how many neurons it would take for a shallow neural network (i.e. 1 hidden layer) to approximate
nonlinear functions since it is theoretically possible.
Each neuron can be thought of as a hyperplane in R2, which is a line. I decided to plot these
hyperplanes that are constructed using the weights and biases from each individual neuron and see how
the accuracy of the neural network changes as we increase the number of neurons (and hyperplanes).

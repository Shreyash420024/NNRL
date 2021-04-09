# NNRL
Neural Networks 
The following program is an attempt to implement a XOR neural network using Numpy.
Numpy is a tool that allows us to use the mathematical operations like matrices and things 
like 2D and 3D arrays seamlessly.Torch has been used inorder to use pytorch.Apart from the
importing numpy, packages like nn(Neural Network),optim (optimiser),matplotlib(Graph plotter)
has been used.After this we have two tensors,thinking behind this would be that we are inputting
in the first tensor whereas the second tensor represents the output(reference here is to the the
XOR truthtable). After this we have inherited the nn module in the class XOR wherein we are 
initializing parameters. Here lin1 and lin2 are the matrices of weights for 1st layer and 2nd layer meaning
the input and the hidden layer.Forward is the function where we feed these values as in assume a certain random 
weight and compute the cost.After this we have called the functions like MSEloss,SGD from the nn and optim package
respectively inorder to calculate the loss i.e., the difference between the values we have initialized and the values 
that the program will calculate and the optimizer decrease the time in which it will achieve the intended value.
Then training the model is the block where the function forward is called.Here the objective is to back propogate
and reset the weights in order to make the final loss zero.The final paragraph only helps us to visualize is better 
and has a set of functions from the matplotlib to plot a graph.

##Micrograd
In this repo, we have implemented backprop as well as the most basic but scalable neural nets from scratch. 
The implementation is from the most fundamental level and mirrors the approach taken by pytorch.
micrograd.py defines a class which handles the weights and biases as variables, and has a built-in gradient function,
which utilizes chain rule to implement backprop.
nn.py defines the Neuron, the Layer and the MLP class which builds on top of the previous one, to implement the Neural Net.

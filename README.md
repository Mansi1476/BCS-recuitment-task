## NEURAL NETWORK
#### Neural Networks are the model inspired by the functioning of the human brain. Networks receives a series of input values and each of these inputs reaches a node called neuron. The neurons of the network are in turn grouped into layers that form the neural network.
### NEURON(NODE)
#### It is the basic unit of neural network. It gets certain number of inputs and bias value.
### WEIGHT
#### Weight is the parameter within a neural network that transforms input data within the networks's hidden layers. Each node has a parameter known as wight.
### BIAS
#### It is an extra input to neurons. Biases makes up the difference between the function's output and its intented output.
### ACTIVATION FUNCTION 
#### Activation functions are used to introduce non-linearity to neural networks. It squashes the values in a smaller range viz. a Sigmoid activation function squashes values between a range 0 to 1. 
### FORWARD PROPAGATION
#### Forward propagation is a process of feeding input values to the neural network and getting an output which we call predicted value. Sometimes we refer forward propagation as inference.
### BACKWARD PROPAGATION
#### Backward-Propagation uses chain rule of Differential Calculus. In chain rule first we calculate the derivatives of error value(To calculate error we compare the predicted value with the actual output value) with respect to the weight values of the last layer. We call these derivatives, gradients and use these gradient values to calculate the gradients of the second last layer. We repeat this process until we get gradients for each and every weight in our neural network. Then we subtract this gradient value from the weight value to reduce the error value. In this way we move closer (descent) to the Local Minima(means minimum loss).
### LEARNING RATE
#### When we train neural networks we usually use Gradient Descent to optimize the weights. At each iteration we use back-propagation to calculate the derivative of the loss function with respect to each weight and subtract it from that weight. Learning rate determines how quickly or how slowly you want to update your weight(parameter) values.

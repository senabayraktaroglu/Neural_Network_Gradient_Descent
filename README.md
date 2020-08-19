# Neural_Network_Gradient_Descent
Neural network algorithm with gradient descent is implemented without using a neural network library.


Equation derivations for one hidden layer
Figure 1 Simple neural network architecture with 1 hidden layer

In the backprogation algorithm, first error will be calculated using feed forward.

A multi layer neural network is implemented with using back propagation
algorithm, mini-batch gradient descent and momentum. Dierent hyperparameters
are experimented to nd optimal model. First size of mini batch experimented
when number of hidden units is 15. The best batch size found as 10.
Also while initializing weights, standart deviation of random initialization set
as m􀀀1=2 where m is number of inputs to hidden unit. After decided to batch
size, it is experimented with dierent number of hidden unit and best found as
15. Figure 1 shows loss, accuracy of positive, accuracy of negative, accuracy at
total when batch size is 10 and number of hidden units in rst layer is 15. Also
momentum coecient is selected as 0.9

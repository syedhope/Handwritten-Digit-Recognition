Neural Networks
----------------
The difficulty of visual pattern recognition becomes apparent if you attempt to write a computer program to recognize digits. Neural networks approach the problem in a different way. The idea is to take a large number of handwritten digits, known as training examples. And then develop a system which can learn from those training examples. In other words, the neural network uses the examples to automatically infer rules for recognizing handwritten digits. Furthermore, by increasing the number of training examples, the network can learn more about handwriting, and so improve its accuracy. So while I've shown just 100 training digits above, perhaps we could build a better handwriting recognizer by using thousands or even millions or billions of training examples.

Program
-------
Computer program implements a neural network that learns to recognize handwritten digits. The program is just 74 lines long, and uses no special neural network libraries. But this short program can recognize digits with an accuracy over 96 percent, without human intervention. 

Implementation
--------------
A Neural network with just two layers - an input and an output layer, no hidden layer - with 784 and 10 neurons, respectively. We Train the network using stochastic gradient descent.
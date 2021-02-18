# ANN Image Classification

Two algorithms are implemented for image classification: 
1) ANN using numpy: features multiple layers, custom # of neurons/layer, multiple activation function (sigmoid, relu), mini-batch gradient descent.
2) CNN using tensorflow: features multiple convolutional layers with dropout.

## Usage
Run ANN.py on CL with the following arguments:

--dataset: 'mnist' or 'iris' (default 'mnist')<br/>
--alg: 'guesser', 'custom_net', or 'tf_net' (default 'custom_net')<br/> 
--epochs: int (default 16)<br/>
--minibatches: bool (default True). 
--mbs: int (default 100). 
--lr: float (default 5). 
--act: 'sigmoid' or 'relu' (default 'sigmoid'). 
--layers: list (default [50]). 

# XOR_Problem
A basic test case for the Neural Network. Code and weights are available

For more info on the XOR problem and its relation to NeuralNetworks/Perceptrons please see https://en.wikipedia.org/wiki/Feedforward_neural_network#Perceptron

The neural network was designed with two input nodes, a hidden layer with three nodes and an output layer with one node. The sigmoid activation function was used for all layers.
   [2,3,1]
The weights and biases are:

| W1 (3x2)          | B1 (3x1) |            W2 (1x3)       | B2 (1x1) |  
|-------------------|----------|---------------------------|----------|
| -4.88953  7.13094 | 1.75752  |                           |          | 
| 6.617720 -3.36387 | 0.515415 | -6.96264 -6.96207 -5.92634| 10.5787  |
| -5.30434 -5.67206 | 1.15333  |                           |          |


![Cost vs  Epochs for XOR problem](https://github.com/user-attachments/assets/606bb6b6-cc96-423e-9d5a-b57bfb266f60)

Some sample outputs

|x  | y | x^y |  x^y (NN) |
|---|---|-----|-----------|
| 0 | 1 |  1  | 0.986066  |  
| 1 | 0 |  1  | 0.98242   |
| 1 | 1 |  0  | 0.0153082 |
| 0 | 0 |  0  | 0.0183879 |

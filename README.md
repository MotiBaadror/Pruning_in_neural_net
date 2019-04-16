# Pruning in neural network
#### Given a layer of a neural network ReLU(xW) are two well-known ways to prune it:
1. Weight pruning: set individual weights in the weight matrix to zero. This corresponds to deleting connections as in the figure above. Here, to achieve sparsity of k% we rank the individual weights in weight
matrix W according to their magnitude (absolute value), and then set to zero the smallest k%.
2. Unit/Neuron pruning: set entire columns to zero in the weight matrix to zero, in
effect deleting the corresponding output neuron. Here to achieve sparsity of k% we rank the the columns of a weight matrix
according to their L2-norm and delete the smallest k%.
## Dataset used in this analysis is MNIST fashin data.

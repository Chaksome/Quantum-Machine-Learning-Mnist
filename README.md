# Machine-Learning-Mnist

The project finally realized the handwritten digit recognition by CNN on MNIST, the network structure diagram is described above, the model is saved in GitHub, and the optimal result is over 99.7\%.

In addition, the tensor network algorithm of MPS and PEPS was implemented for handwritten digit recognition, and the algorithm was implemented in python according to the reference (paper without code), and exceeded the optimal results of MPS and PEPS in the paper (the figure below shows the results in the paper). It is mentioned in the paper that the initial step of tensor network is to transform the original data into multiple vector direct products, and in fact, the optimal transformation method can be found by CNN convolution, which can improve the accuracy of tensor network.
However, the combination of CNN and PEPS has not been achieved in the end, and this is a direction that can be done subsequently.


# Machine-Learning-Mnist
Find my code on https://github.com/Chaksome/Machine-Learning-Mnist

The project finally realized the handwritten digit recognition by CNN on MNIST, the network structure diagram is described above, the model is saved in GitHub, and the optimal result is over 99.7\%.（Machine Learning Project）（2022.1.21）

In addition, the tensor network algorithm of MPS and PEPS was implemented for handwritten digit recognition, and the algorithm was implemented in python according to the reference, and exceeded the optimal results of MPS and PEPS in the paper. It is mentioned in the paper that the initial step of tensor network is to transform the original data into multiple vector direct products, and in fact, the optimal transformation method can be found by CNN convolution, which can improve the accuracy of tensor network. （Quantum Algorithm Project）（2022.6.9）

However, the combination of CNN and PEPS has not been achieved in the end, and this is a direction that can be done subsequently.


myCNN=======>>>>>realize the CNN algorithm on MNIST (hit 99.77\%)

myNoise=======>>>>>add noise to my model and see if it will collapse

myAblationExperiment=======>>>>>Optimize the CNN model

myMPS=======>>>>realize the MPS algorithm on MNIST(98.41\%for bond_dimension = 6)

myPEPS=======>>>>>realize the PEPS algorithm on MNIST(96.67\% for bond_dimension = 3)

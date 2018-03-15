# Residual-Network
A pytorch implement of ResNet
-----
## introduction

Both directories are using ResNet-20, training and testing on different datasets -- CIFAR10 and Fashion-MNIST.

I trained the network on CIFAR-10 for 10 epochs, and got a accuracy of 80% on the testing set.

The Fashion-MNIST training set was trained for only 3 epochs due to resource limit, and 93% accuracy on testing set was achieved.

These two programs are designed mainly for CPU computing, so GPU is not required. However, using `.cuda()` can easily change the codes to GPU version.

## Environment

Python 3.x

Pytorch 0.3.0

torchvision

Tensorflow (to provide support to tensorboardX)

Numpy


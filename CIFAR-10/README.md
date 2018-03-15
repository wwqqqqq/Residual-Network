## requirement

pytorch

torchvision

tensorboardX

matplotlib

## files

**ResNet18.ipynb**   => a python program that implements a 20-layer residual network (only supports CPU). The network is trained and tested on CIFAR-10 dataset. Training process has 10 epoches. ResNet is based on this paper: *[Deep Residual Learning for Image Recognition](http://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)*.

**result**  => The loss (CrossEntropyLoss) and accuracy of the training and testing set, during training process. The Xlabel of training set results is batches (batch_size=128). The Xlabel of testing set results is epoches.

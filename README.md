# CapsuleNetworks-TensorFlow
This is my implementation of Capsule Networks from this [paper](https://arxiv.org/abs/1710.09829). 
The entire source code is based on TensorFlow. I have put it in a jupyter notebook for easy reading. 

## The Network
As told in the paper, Capsule networks aim to understand equivariance in images. This is achieved via the Dynamic Routing algorithm. There is further explanation of in the source code. Here is a high level view of all the layers in the Neural Network.
<img src = 'results/neural_network.png'>

## To-Do
Support has not been added for the reconstruction process shown in the paper, the implementation is only for classification as of now.

## To Run
Open the jupyter notebook and run all the cells.
'''
$ jupyter notebook
'''
Run all cells.

## Hyper Parameters & Results
The model has been tuned to the following hyper parameters:
* batch_size = 128
* epochs = 10
* num_iters = 3 (Number of routing iterations.)
* Average test accuracy obtained is 99.1%

## References & Thanks
I have referred to the following repositories for ideas and when I was stuck on implementation.
* [naturomics](https://github.com/naturomics/CapsNet-Tensorflow)
* [XifengGuo](https://github.com/XifengGuo/CapsNet-Keras)
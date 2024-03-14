# Work Introduction

## "Repro_Sampling_Method"
#### Model: Fully Connected NN with arbituary architecture parameters (parameters are subject to search in a context of GRID SEARCH.)
#### Data: Float numbers that are standard normally generated with additional standard normal random noise.
#### Puprpose: According to Repro_Sampling Method (under development) create a Performance Guaranteed Deep Neuron Network model. The model has functionalities 1) follows data simulation study, generate data under experiment context 2) grid search on architecture parameters 3) perform nuclear mapping calculation 4) perform Monte-Calo simulation on model performance and Borel Set calculation. After step 4, model will generate a performance guaranteed Borel Interval for architecture parameters.

## "LeNet_CNN_CIFAR10"
#### Model: LeNet 
#### Data: CIFAR10 (SOURCE: https://www.cs.toronto.edu/~kriz/cifar.html)
#### Data Description: The CIFAR-10 and CIFAR-100 are labeled subsets of the 80 million tiny images dataset. They were collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
#### Purpose: Collect image classification performace on CNN model "LeNet". Expect accuracy 50%.

## "NN_with_Only_Numpy"
#### Model: Fully Connected NN with PyTorch Framework, Fully Connected NN with Numpy Only 
#### Data: MNIST (SOURCE: https://www.tensorflow.org/datasets/catalog/mnist)
#### Data Description: The MNIST database (Modified National Institute of Standards and Technology database) is a large collection of handwritten digits. It has a training set of 60,000 examples, and a test set of 10,000 examples. Each image is collected with 20 x 20 pixels.
#### Purpose: Compare performance difference on the the same image classification task on (1) Model using PyTorch Framework vs (2) Model coded using only Numpy. Expect test accuracy difference less <= 3%.


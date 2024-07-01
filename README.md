# Work Introduction

## "Repro_Sampling_Method"
Model: Fully Connected NN with arbitrary architecture parameters (parameters are subject to search in a context of GRID SEARCH.)\
Data: Float numbers that are standard normally generated with additional standard normal random noise.\
Puprpose: According to Repro_Sampling Method (under development) create a Performance Guaranteed Deep Neuron Network model. The model has functionalities: 
1) follows data simulation study, generate data under experiment context 
2) grid search on architecture parameters 
3) perform nuclear mapping calculation
4) perform Monte-Calo simulation on model performance and Borel Set calculation. \
After step 4, model will generate a performance guaranteed Borel Interval for architecture parameters.

## "LeNet_CNN_CIFAR10"
Model: LeNet \
Data: CIFAR10 (SOURCE: https://www.cs.toronto.edu/~kriz/cifar.html) \
Data Description: The CIFAR-10 and CIFAR-100 are labeled subsets of the 80 million tiny images dataset. They were collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.\
Purpose: Collect image classification performace on CNN model "LeNet". Expect accuracy 50%.

## "NN_with_Only_Numpy"
Model: Fully Connected NN with PyTorch Framework, Fully Connected NN with Numpy Only \
Data: MNIST (SOURCE: https://www.tensorflow.org/datasets/catalog/mnist) \
Data Description: The MNIST database (Modified National Institute of Standards and Technology database) is a large collection of handwritten digits. It has a training set of 60,000 examples, and a test set of 10,000 examples. Each image is collected with 20 x 20 pixels.\
Purpose: Compare performance difference on the the same image classification task on (1) Model using PyTorch Framework vs (2) Model coded using only Numpy. Expect test accuracy difference less <= 3%.

## "simplified_banking_system" 
A Python implementation of a simplified banking system. It is an object-oriented program that simulates basic features of a banking application, including account creation, deposits, transfers, payments, and account merging. \
All levels: \
Level 1: Basic operations like account creation, deposits, and money transfers between accounts. \
Level 2: Ranking accounts based on the total amount of outgoing transactions.\
Level 3: Scheduling payments with cashback and checking the status of scheduled payments.\
Level 4: (Planned) Merging two accounts while retaining balance and transaction histories.

## "simplified_banking_system_rust"
A re-implementation of "simplified_banking_system". It is naive implementation in Rust language. This implementation should cover all the specified functionalities \
Include Level 1 to level 4: account creation, deposits, money transfers between accounts, ranking accounts, scheduling payments, checking the status of scheduled payments, merging two accounts.

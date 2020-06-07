# NN-Models

## Table of Contents

* [Description](#description)
* [Tools & Dependencies](#tools)

## Description

The objective of the notebooks is to serve as boilerplate of different NN methods and optimization modules for other projects. It is used a database of simplified images of clothes to train the neural networks and to classify other clothes from a test set.

I did it on my own but with instructions from [udacity](https://www.udacity.com) for their pytorch course. You can find more about it in their [github](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/intro-to-pytorch)

`Fashion-MNIST` is a dataset of [Zalando](https://jobs.zalando.com/tech/)'s consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Description from [here](https://github.com/zalandoresearch/fashion-mnist)

## Tools & Dependencies

Pytorch is used to create a neural network. The [helper.py](helper.py) file is used to visualization and to see the distinct probabilities of the clothes being the one indicated.

Other python libraries used are:
* Matplotlib
* Torchvision
* Numpy

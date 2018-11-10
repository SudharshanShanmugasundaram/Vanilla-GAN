# Vanilla-GAN

This is an implementation of vanilla generative adversarial networks (VGANs) using PyTorch on MNIST dataset.

# Generative Adversarial Networks

[Generative Adversarial Networks](https://en.wikipedia.org/wiki/Generative_adversarial_network) (GANs) are a class of artificial intelligence algorithms used in unsupervised machine learning, implemented by a system of two neural networks contesting with each other in a zero-sum game framework. They were introduced by Ian Goodfellow et al. in 2014.This technique can generate photographs that look at least superficially authentic to human observers, having many realistic characteristics (though in tests people can tell real from generated in many cases).

# Dataset

The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.
It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting.

The dataset can be download from here : [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)

# Requirements
1. PyTorch
2. Python
3. Torchvision

```utils.py file has been taken from other source.It serves the purpose of visualization of the performance of the model on the dataset```

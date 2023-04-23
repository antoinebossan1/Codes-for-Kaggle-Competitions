# Comparison-of-ResNet-18-and-LeNet-5-Models-for-MNIST-Image-Classification


MNIST Image Classification with ResNet-18 and LeNet-5 Models

This project compares the performance of two popular deep learning models, ResNet-18 and LeNet-5, for image classification on the MNIST dataset from the related Kaggle Competition (https://www.kaggle.com/competitions/digit-recognizer). 


## Table of Contents

- [Introduction](#introduction)
- [Results](#results)
- [References](#references)

# Introduction

The MNIST dataset is a collection of 70,000 handwritten digits, 0 through 9, each represented as a 28x28 grayscale image. The goal of this project is to train deep learning models to correctly classify these images into their corresponding digits. A sample of the MNIST dataset: 

<img width="1069" alt="Capture d’écran 2023-04-19 à 17 00 19" src="https://user-images.githubusercontent.com/121366737/233024742-5b5a6ce8-5af0-496a-8007-4eea53c62c28.png">


ResNet-18 is a convolutional neural network architecture that was introduced in the paper "Deep Residual Learning for Image Recognition" by Kaiming He et al. in 2016. The model is composed of 18 layers and uses residual connections to mitigate the vanishing gradient problem in deep networks. 

LeNet-5 is a convolutional neural network architecture that was introduced in the paper "Gradient-Based Learning Applied to Document Recognition" by Yann LeCun et al. in 1998. The model is composed of 5 layers and was originally designed specially for this dataset.

It is worth wondering whether, although ResNet-18 is a more complex CNN than LeNet-5, it will perform better on the MNIST dataset, given that LeNet-5 was specifically designed for it.

# Results

ResNet-18 slightly outperformed LeNet-5 on the MNIST dataset. After training both models for 10 epochs, we achieved a test accuracy of 0.98846 for ResNet-18 and 0.9815 for LeNet-5.

<img width="1159" alt="Capture d’écran 2023-04-19 à 13 36 55" src="https://user-images.githubusercontent.com/121366737/232976603-31fb9168-e01a-42db-a28b-1678427ef15e.png">



# References
1. Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun. "Deep Residual Learning for Image Recognition." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2016.
2. Yann LeCun, Léon Bottou, Yoshua Bengio, and Patrick Haffner. "Gradient-Based Learning Applied to Document Recognition." Proceedings of the IEEE, 1998.



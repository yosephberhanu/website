---
layout: page
title: Backprop from scratch
description: Implemented backpropagation for multi-layer perceptrons (MLPs) and convolutional neural networks (CNNs)
img: assets/img/personal/backprop.jpg
importance: 1
comments: true
category: fun
tags: ["Machine Learning", "Python", "CNN"]
related_publications: no
---
In a [personal project], I worked on a sample implementation of [Automatic Differentiation](https://github.com/yosephberhanu/auto-diff/) and [Neural Networks]((https://github.com/yosephberhanu/ylearn)) partly based on tutorial from [sentdex](https://www.youtube.com/watch?v=Wo5dMEP_BbI&list=PLQVvvaa0QuDcjD5BAw2DxE6OF2tius3V3) and examples from [Matthew Johnson
](https://github.com/mattjj/autodidact) and [AutoGrad](https://github.com/HIPS/autograd). 

As part of a course requirment for CS5814 at VT I implemented backpropagation for multi-layer perceptrons (MLPs) and convolutional neural networks (CNNs). It provided me hands-on experience with these neural network architectures

First, I implemented a multi-layer neural network to predict image pixel values (the 3D RGB color values) given the 2D (x,y) coordinates of the image. Additionally, I experimented with various transformations of the input coordinates to explore their impact on training.

Then, I implemented a simple convolutional neural network using NumPy. The task was to predict digit values from given images using a regression-style loss. This involved directly writing out the convolution process and implementing the training procedure for the CNN. I attempted to reconstruct input images using the convolutional network. The goal was to obtain reasonable reconstructions that closely resemble the input digits. This involved adding additional convolutional layers, experimenting with more filters, and applying data augmentation techniques.

#### Key Features:
- Implemented a multi-layer neural network from scratch.
- Predicted RGB values of images based on 2D coordinates.
- Explored the impact of input transformations on training efficiency.
- Implemented a convolutional neural network from scratch.
- Predicted values of digit images using regression-style loss.
- Demonstrated the training process and analyzed the results.

#### Tools and Technologies:
- Python
- NumPy

### Source Code
The complete source code for these projects is available on GitHub: [Automatic Differentiation](https://github.com/yosephberhanu/auto-diff/), [Simple Neural Networks](https://github.com/yosephberhanu/ylearn), [Multi-layer neural network](#).


__Image Credit__: https://blog.zhaytam.com/2018/08/15/implement-neural-network-backpropagation/
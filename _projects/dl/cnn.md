---
layout: page
title: CNN Architectures
description: Reimplementation of influential Convolutional Neural Network architectures.
img: assets/img/personal/cnn.jpg
importance: 1
category: fun
tags: ["Deep Learning", "Python", "CNN", "PyTorch"]
related_publications: false
---
This project focuses on reimplementing influential Convolutional Neural Network (CNN) architectures from key papers in CNN history. While some architectures are simplified due to resource constraints, their core features and functionality are faithfully preserved to showcase their impact on deep learning.

---

### Architectures:

#### [LeNet (1998)](https://yann.lecun.com/exdb/lenet/)
- **Developed by**: [Yann LeCun](https://en.wikipedia.org/wiki/Yann_LeCun)  
- **Key Features**:  
  - One of the earliest CNNs, designed for digit recognition (e.g., MNIST dataset).  
  - Simple and effective architecture featuring convolutional layers, pooling layers, and fully connected layers.  
- **Use Case**: Handwritten digit classification.  
- **My Implementation**:  
  - Focuses on **LeNet-5**, the most impactful version in the LeNet family.  
  - Introduced a structured combination of convolutional, pooling, and fully connected layers.  
  - Showcased scalability for large-scale digit classification tasks and proved the practicality of gradient-based optimization in CNNs.  
  - Laid the groundwork for many modern CNN designs and remains a classic benchmark in deep learning.  
  - View the Jupyter Notebook implementation [here](https://github.com/yosephberhanu/cnn/blob/master/LeNet/LeNet.ipynb).

---

#### [AlexNet (2012)](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)
- **Developed by**: Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton  
- **Key Features**:  
  - The first CNN to achieve breakthrough performance in the ImageNet competition.  
  - Introduced innovations like ReLU activation and dropout for regularization.  
  - Comprised 5 convolutional layers with max-pooling, followed by 3 fully connected layers.  
- **Use Case**: General image classification.  
- **My Implementation**:  
  - Implements AlexNet for the [Food-101](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) dataset, a large collection of food images across 101 categories.  
  - The network was built and trained from scratch using PyTorch, without relying on pre-trained weights.  
  - Images were preprocessed and resized to match AlexNet’s input requirements (224x224).  
  - Randomized weight initialization and dropout layers were used to address overfitting challenges.  
  - Demonstrates AlexNet's robustness in adapting to challenging datasets with diverse classes and uncleaned test data.  
  - View the Jupyter Notebook implementation [here](https://github.com/yosephberhanu/cnn/blob/master/AlexNet/AlexNet.ipynb).

---

### Tools and Resources:
- **Programming Languages**: Python  
- **Deep Learning Framework**: PyTorch  
- **Compute Resources**: [VT ARC](https://arc.vt.edu/) cluster (for GPU access)

---

### Source Code
The complete source code for this project is available on [GitHub](https://github.com/yosephberhanu/cnn).

---

**Cover Image Credit**: [Kh. Nafizul Haque](https://www.linkedin.com/pulse/what-convolutional-neural-network-cnn-deep-learning-nafiz-shahriar/)  

---
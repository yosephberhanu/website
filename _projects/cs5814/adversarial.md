---
layout: page
title: Adversarial attack on DL
description: A demonstration fo adversarial attack on CNN based image classification models
img: assets/img/personal/adversarial.png
importance: 1
category: fun
tags: ["Deep Learning", "Python", "CNN", "Adversarial Attack"]
related_publications: false
---
This projecct involves using automatic differentiation's capabilities to explain model classifications and create adversarial examples. I first explored how gradients can be used to explain which portion of the input the model relied on for making its classification. Then I implemented [Grad-CAM](https://arxiv.org/pdf/1610.02391.pdf) from scratch.

Then explored two basic adversarial methods in order to cause ResNet18 to predict another class by perturbing the input images. To improve reconstruction quality.

#### Key Features:
- Used gradients to highlight important image regions.
- Impelemented Grad-CAM from scratch
- Implemented adversarial methods to create misleading inputs.
- Analyzed model behavior and robustness.

#### Tools and Technologies:
- Python
- PyTorch

### Source Code
The complete source code for this project is available on [GitHub](#).
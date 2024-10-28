---
layout: page
title: Conditional Variational Autoencoder
description: A demonstration of VAE
img: assets/img/personal/vae.png
importance: 1
category: fun
tags: ["Deep Learning", "Python", "VAE", "Generative AI"]
related_publications: false
---
## Project Description
In this project, I implemented a variational autoencoder (VAE), consisting of an encoder and decoder. The VAE was trained using a cross-entropy loss and a regularization term to enforce a prior distribution on learned variables. To improve generated image quality I replaced reconstruction loss with perceptual loss. I also extracted features from VGG16 for comparison in feature space and performed interpolation between samples in latent space and visualized translations within and across classes.

#### Key Features:
- Implemented conditional variational autoencoder.
- Trained VAE on image reconstruction task.
- Analyzed and visualized latent space interpolations.

#### Tools and Technologies:
- Python
- PyTorch

### Source Code
The complete source code for this project is available on [GitHub](#).
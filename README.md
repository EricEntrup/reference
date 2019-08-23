# Deep Learning Material


## Contents

- **Datasets**
  - MNIST
  - Iris
  - ImageNet
  - COCO
  

- **Loss Functions**
  - Mean Square Error
  - Cross Entropy
  - Negative Log Likelihood
- **Models**
  - [**EDSR**](#EDSR)
  - [**Resnet**](#Resnet)
  - [**Wavenet**](#WWavenet)

Note: AlexNet; VGG; SqueezeNet; Densenet; Inception


## Resnet
![](https://img.shields.io/badge/code-pytorch-1abc9c?style=plastic)
![](https://img.shields.io/badge/example-classification-orange?style=plastic)
![](https://img.shields.io/badge/data-mnist-1f425f?style=plastic)

**Paper:** [Deep Residual Learning for Image Recognition](https://arxiv.org/pdf/1512.03385.pdf)

**Example:** [Classification of Digits using Resnet]()

**Take Away:** We expect that a deep network will be able to perform as well or better than a shallow netowrk. This is expected because we hope that for every additional in the deep network will be able to learn an identity mapping. However, through experiments, this was shown to be false. The ResNet paper proposes a solution to this *degradation* problem by introducing residual connections.



**Architecture:**


## Wavenet

**Paper:** https://arxiv.org/pdf/1512.03385.pdf

**Example:**

**Take Away:**

**Summary:**

**Architecture:**


## EDSR

**Paper:** https://arxiv.org/pdf/1512.03385.pdf

**Example:**

**Take Away:**

**Summary:**

**Architecture:**


## ESRGAN

**Paper:** https://arxiv.org/pdf/1512.03385.pdf
**Example:**
**Take Away:**
**Summary:**
**Architecture:**




**Random Notes**

Vanishing/exploding gradients can be solved by normalizing initializations and intermediate normalization layers.

deeper networks can result in accuracy saturation, but not caused by overfitting.

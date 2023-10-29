---
title: "Scalar Invariant Networks with Zero Bias"
collection: publications
permalink: /workshop/2023-10-25-Scalar_Invariant_Networks_with_Zero_Bias
excerpt: ''
date: 2023-10-25
venue: 'NeurReps@NeurIPS'
paperurl:
citation: 'Geng, C., Xu, X., Ye, H., & Si, X. (2022). Scalar Invariant Networks with Zero Bias. arXiv preprint arXiv:2211.08486.'
---

Just like weights, bias terms are learnable parameters in many popular machine learning models, including neural networks. Biases are believed to enhance the representational power of neural networks, enabling them to tackle various tasks in computer vision. Nevertheless, we argue that biases can be disregarded for some image-related tasks such as image classification, by considering the intrinsic distribution of images in the input space and desired model properties from first principles. Our empirical results suggest that zero-bias neural networks can perform comparably to normal networks for practical image classification tasks. Furthermore, we demonstrate that zero-bias neural networks possess a valuable property known as scalar (multiplicative) invariance. This implies that the network's predictions remain unchanged even when the contrast of the input image is altered. We further extend the scalar invariance property to more general cases, thereby attaining robustness within specific convex regions of the input space. We believe dropping bias terms can be considered as a geometric prior when designing neural network architecture for image classification, which shares the spirit of adapting convolutions as the translational invariance prior.

[Download paper here](https://arxiv.org/pdf/2211.08486.pdf)
---
order: 4
month: 1
year: 2023
date: 2023-05-17
title: 'Adversarial Training for Neural Networks'
repo: 'https://github.com/siavava/deep-learning/tree/main/homeworks/02'
tech:
  - Python
  - PyTorch
  - Deep Learning
featured: true
navigation: false
tag: 'deep learning'
---

Experimentation with various adversarial training techniques for neural networks.
Adversarial training is useful to improve the robustness of neural networks to
adversarial attacks &mdash; which often happen as noise in the input data.
Techniques explored include:
- [Data augmentation][augmentation], which helps the model have more data to learn from.
  New samples are generated by randomly cropping and/or flipping some images.
  We also add [pertubations][pertubation], to a random subset of images,
  which helps the model learn to be robust to noise.
- [Dropout][dropout], which entails randomly blocking a subset of the neurons in the network
  from transmitting information during training. This helps huge models avoid overfitting,
  thus generalize better.
- [Ensemble learning][ensemble], which entails training multiple models on the same dataset
  and then averaging their predictions. This helps the model generalize better
  by mitigating the effects of a single model overfitting.

[augmentation]: https://www.datacamp.com/tutorial/complete-guide-data-augmentation
[pertubation]:  https://www.sciencedirect.com/science/article/pii/S0167865521002440
[dropout]:      https://paperswithcode.com/method/dropout
[ensemble]:     https://www.sciencedirect.com/science/article/pii/S1319157823000228

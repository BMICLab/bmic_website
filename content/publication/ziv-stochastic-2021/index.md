---
title: "Stochastic weight pruning and the role of regularization in shaping network structure"
date: 2021-10-01
publishDate: 2023-09-04T14:13:46.268845Z
authors: ["Yael Ziv", "Jacob Goldberger", "Tammy Riklin Raviv"]
publication_types: ["2"]
abstract: "The pressing need to reduce the capacity of deep neural networks has stimulated the development of network dilution methods and their analysis. In this study we present a framework for neural network pruning by sampling from a probability function that favors the zeroing of smaller parameters. This procedure of stochastically setting network weights to zero is done after each parameter updating step in the network learning algorithm. As part of the proposed framework, we examine the contribution of L1 and L2 regularization to the dynamics of pruning larger network structures such as neurons and filters while optimizing for weight pruning. We then demonstrate the effectiveness of the proposed stochastic pruning framework when used together with regularization terms for different network architectures and image analysis tasks. Specifically, we show that using our method we can successfully remove more than 50% of the channels/filters in VGG-16 and MobileNetV2 for CIFAR10 classification; in ResNet56 for CIFAR100 classification; in a U-Net for instance segmentation of biological cells; and in a CNN model tailored for COVID-19 detection. For these filter-pruned networks, we also present competitive weight pruning results while maintaining the accuracy levels of the original, dense networks."
featured: false
publication: "*Neurocomputing*"
tags: ["COVID-19", "Neural network compression", "Node pruning", "Pruning dynamics", "Weight decay", "Weight pruning"]
url_pdf: "https://www.sciencedirect.com/science/article/pii/S0925231221011917"
doi: "10.1016/j.neucom.2021.08.007"
---


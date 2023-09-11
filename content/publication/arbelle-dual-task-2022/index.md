---
title: "Dual-Task ConvLSTM-UNet for Instance Segmentation of Weakly Annotated Microscopy Videos"
date: 2022-08-01
publishDate: 2023-09-04T14:13:46.268483Z
authors: ["Assaf Arbelle", "Shaked Cohen", "Tammy Riklin Raviv"]
publication_types: ["2"]
abstract: "Convolutional Neural Networks (CNNs) are considered state of the art segmentation methods for biomedical images in general and microscopy sequences of living cells, in particular. The success of the CNNs is attributed to their ability to capture the structural properties of the data, which enables accommodating complex spatial structures of the cells, low contrast, and unclear boundaries. However, in their standard form CNNs do not exploit the temporal information available in time-lapse sequences, which can be crucial to separating touching and partially overlapping cell instances. In this work, we exploit cell dynamics using a novel CNN architecture which allows multi-scale spatio-temporal feature extraction. Specifically, a novel recurrent neural network (RNN) architecture is proposed based on the integration of a Convolutional Long Short Term Memory (ConvLSTM) network with the U-Net. The proposed ConvLSTM-UNet network is constructed as a dual-task network to enable training with weakly annotated data, in the form of approximate cell centers, termed markers, when the complete cells’ outlines are not available. We further use the fast marching method to facilitate the partitioning of clustered cells into individual connected components. Finally, we suggest an adaptation of the method for 3D microscopy sequences without drastically increasing the computational load. The method was evaluated on the Cell Segmentation Benchmark and was ranked among the top three methods on six submitted datasets. Exploiting the proposed built-in marker estimator we also present state-of-the-art cell detection results for an additional, publicly available, weekly annotated dataset. The source code is available at https://gitlab.com/shaked0/lstmUnet."
featured: true
publication: "*IEEE Transactions on Medical Imaging*"
tags: ["Annotations", "Computer architecture", "Deep learning", "image segmentation", "Image segmentation", "image sequences", "Microprocessors", "microscopy", "Microscopy", "neural networks", "object segmentation", "recurrent neural networks", "Three-dimensional displays", "Training"]
doi: "10.1109/TMI.2022.3152927"
---


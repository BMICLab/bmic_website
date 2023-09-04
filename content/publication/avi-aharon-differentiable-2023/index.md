---
title: "Differentiable Histogram Loss Functions for Intensity-based Image-to-Image Translation"
date: 2023-01-01
publishDate: 2023-09-04T14:13:46.267437Z
authors: ["Mor Avi-Aharon", "Assaf Arbelle", "Tammy Riklin Raviv"]
publication_types: ["2"]
abstract: "We introduce the HueNet - a novel deep learning framework for a differentiable construction of intensity (1D) and joint (2D) histograms and present its applicability to paired and unpaired image-to-image translation problems. The key idea is an innovative technique for augmenting a generative neural network by histogram layers appended to the image generator. These histogram layers allow us to define two new histogram-based loss functions for constraining the structural appearance of the synthesized output image and its color distribution. Specifically, the color similarity loss is defined by the Earth Mover's Distance between the intensity histograms of the network output and a color reference image. The structural similarity loss is determined by the mutual information between the output and a content reference image based on their joint histogram. Although the HueNet can be applied to a variety of image-to-image translation problems, we chose to demonstrate its strength on the tasks of color transfer, exemplar-based image colorization, and edges to photo, where the colors of the output image are predefined. The code is available at https://github.com/mor-avi-aharon-bgu/HueNet.git"
featured: false
publication: "*IEEE Transactions on Pattern Analysis and Machine Intelligence*"
tags: ["Deep learning", "Earth Movers Distance", "Generators", "Histogram Layers", "Histograms", "Image color analysis", "Image edge detection", "Image-to-Image Translation", "Intensity Histogram Loss Functions", "Mutual Information Loss", "Semantics", "Task analysis"]
doi: "10.1109/TPAMI.2023.3278287"
---


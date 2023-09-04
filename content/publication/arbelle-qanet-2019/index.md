---
title: "QANet -- Quality Assurance Network for Image Segmentation"
date: 2019-11-01
publishDate: 2023-09-04T14:40:54.725727Z
authors: ["Assaf Arbelle", "Eliav Elul", "Tammy Riklin Raviv"]
publication_types: ["0"]
abstract: "We introduce a novel Deep Learning framework, which quantitatively estimates image segmentation quality without the need for human inspection or labeling. We refer to this method as a Quality Assurance Network -- QANet. Specifically, given an image and a `proposed' corresponding segmentation, obtained by any method including manual annotation, the QANet solves a regression problem in order to estimate a predefined quality measure with respect to the unknown ground truth. The QANet is by no means yet another segmentation method. Instead, it performs a multi-level, multi-feature comparison of an image-segmentation pair based on a unique network architecture, called the RibCage. To demonstrate the strength of the QANet, we addressed the evaluation of instance segmentation using two different datasets from different domains, namely, high throughput live cell microscopy images from the Cell Segmentation Benchmark and natural images of plants from the Leaf Segmentation Challenge. While synthesized segmentations were used to train the QANet, it was tested on segmentations obtained by publicly available methods that participated in the different challenges. We show that the QANet accurately estimates the scores of the evaluated segmentations with respect to the hidden ground truth, as published by the challenges' organizers. The code is available at: TBD."
featured: false
publication: "*arXiv*"
tags: ["Computer Science - Artificial Intelligence", "Computer Science - Computer Vision and Pattern Recognition", "Computer Science - Machine Learning", "Statistics - Machine Learning"]
url_pdf: "http://arxiv.org/abs/1904.08503"
doi: "10.48550/arXiv.1904.08503"
---


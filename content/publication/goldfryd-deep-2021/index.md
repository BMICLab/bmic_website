---
title: "Deep Semi-Supervised Bias Field Correction Of Mr Images"
date: 2021-04-01
publishDate: 2023-09-04T14:13:46.269579Z
authors: ["Tal Goldfryd", "Shiri Gordon", "Tammy Riklin Raviv"]
publication_types: ["1"]
abstract: "A bias field is an artifact inherent to MRI scanners which is manifested by a smooth intensity variation across the scans. We present an innovative generative approach to address the inverse problem of bias field estimation and removal in a semi-supervised manner. The key contribution is the construction of a compound framework of four interacting, adversarial neural networks. Specifically, we simultaneously train a pair of neural networks, one for the reconstruction of the plain bias field and the other for the reconstruction of a bias-free MRI scan, such that the output of each together with the input biased scans define the loss of the other network. A third network, trained as a bias-field discriminator provides an additional loss to the bias field generator while an MRI segmentation network provides an additional loss to the bias-free MRI generator. We trained and validated our framework using real MRI scans with simulated bias fields and tested it on publicly available brain data-sets as well as private data yielding results competitive with state-of-the-art methods. Code is available upon request."
featured: false
publication: "*2021 IEEE 18th International Symposium on Biomedical Imaging (ISBI)*"
tags: ["Adversarial Neural Networks", "Bias field correction", "Biological neural networks", "Brain MRI", "Compounds", "Deep Learning", "Estimation", "Generators", "Image reconstruction", "Inverse problems", "Magnetic resonance imaging"]
doi: "10.1109/ISBI48211.2021.9433889"
---


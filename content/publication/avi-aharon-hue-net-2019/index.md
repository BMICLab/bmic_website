---
title: "Hue-Net: Intensity-based Image-to-Image Translation with Differentiable Histogram Loss Functions"
date: 2019-12-01
publishDate: 2023-09-04T14:40:54.723495Z
authors: ["Mor Avi-Aharon", "Assaf Arbelle", "Tammy Riklin Raviv"]
publication_types: ["0"]
abstract: "We present the Hue-Net - a novel Deep Learning framework for Intensity-based Image-to-Image Translation. The key idea is a new technique termed network augmentation which allows a differentiable construction of intensity histograms from images. We further introduce differentiable representations of (1D) cyclic and joint (2D) histograms and use them for defining loss functions based on cyclic Earth Mover's Distance (EMD) and Mutual Information (MI). While the Hue-Net can be applied to several image-to-image translation tasks, we choose to demonstrate its strength on color transfer problems, where the aim is to paint a source image with the colors of a different target image. Note that the desired output image does not exist and therefore cannot be used for supervised pixel-to-pixel learning. This is accomplished by using the HSV color-space and defining an intensity-based loss that is built on the EMD between the cyclic hue histograms of the output and the target images. To enforce color-free similarity between the source and the output images, we define a semantic-based loss by a differentiable approximation of the MI of these images. The incorporation of histogram loss functions in addition to an adversarial loss enables the construction of semantically meaningful and realistic images. Promising results are presented for different datasets."
featured: false
publication: "*arXiv*"
tags: ["Computer Science - Computer Vision and Pattern Recognition", "Computer Science - Machine Learning"]
url_pdf: "http://arxiv.org/abs/1912.06044"
doi: "10.48550/arXiv.1912.06044"
---


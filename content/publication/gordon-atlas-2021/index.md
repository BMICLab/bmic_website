---
title: "An atlas of classifiers—a machine learning paradigm for brain MRI segmentation"
date: 2021-09-01
publishDate: 2023-09-04T14:13:46.269211Z
authors: ["Shiri Gordon", "Boris Kodner", "Tal Goldfryd", "Michael Sidorov", "Jacob Goldberger", "Tammy Riklin Raviv"]
publication_types: ["2"]
abstract: "We present the Atlas of Classifiers (AoC)—a conceptually novel framework for brain MRI segmentation. The AoC is a spatial map of voxel-wise multinomial logistic regression (LR) functions learned from the labeled data. Upon convergence, the resulting fixed LR weights, a few for each voxel, represent the training dataset. It can, therefore, be considered as a light-weight learning machine, which despite its low capacity does not underfit the problem. The AoC construction is independent of the actual intensities of the test images, providing the flexibility to train it on the available labeled data and use it for the segmentation of images from different datasets and modalities. In this sense, it does not overfit the training data, as well. The proposed method has been applied to numerous publicly available datasets for the segmentation of brain MRI tissues and is shown to be robust to noise and outreach commonly used methods. Promising results were also obtained for multi-modal, cross-modality MRI segmentation. Finally, we show how AoC trained on brain MRIs of healthy subjects can be exploited for lesion segmentation of multiple sclerosis patients."
featured: false
publication: "*Medical & Biological Engineering & Computing*"
tags: ["Brain MRI", "Logistic regression classifiers", "Machine learning", "MS-lesions", "Segmentation"]
url_pdf: "https://doi.org/10.1007/s11517-021-02414-x"
doi: "10.1007/s11517-021-02414-x"
---


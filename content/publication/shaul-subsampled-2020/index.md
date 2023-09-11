---
title: "Subsampled brain MRI reconstruction by generative adversarial neural networks"
date: 2020-10-01
publishDate: 2023-09-04T14:40:57.581552Z
authors: ["Roy Shaul", "Itamar David", "Ohad Shitrit", "Tammy Riklin Raviv"]
publication_types: ["2"]
abstract: "A main challenge in magnetic resonance imaging (MRI) is speeding up scan time. Beyond improving patient experience and reducing operational costs, faster scans are essential for time-sensitive imaging, such as fetal, cardiac, or functional MRI, where temporal resolution is important and target movement is unavoidable, yet must be reduced. Current MRI acquisition methods speed up scan time at the expense of lower spatial resolution and costlier hardware. We introduce a practical, software-only framework, based on deep learning, for accelerating MRI acquisition, while maintaining anatomically meaningful imaging. This is accomplished by MRI subsampling followed by estimating the missing k-space samples via generative adversarial neural networks. A generator-discriminator interplay enables the introduction of an adversarial cost in addition to fidelity and image-quality losses used for optimizing the reconstruction. Promising reconstruction results are obtained from feasible sampling patterns of up to a fivefold acceleration of diverse brain MRIs, from a large publicly available dataset of healthy adult scans as well as multimodal acquisitions of multiple sclerosis patients and dynamic contrast-enhanced MRI (DCE-MRI) sequences of stroke and tumor patients. Clinical usability of the reconstructed MRI scans is assessed by performing either lesion or healthy tissue segmentation and comparing the results to those obtained by using the original, fully sampled images. Reconstruction quality and usability of the DCE-MRI sequences is demonstrated by calculating the pharmacokinetic (PK) parameters. The proposed MRI reconstruction approach is shown to outperform state-of-the-art methods for all datasets tested in terms of the peak signal-to-noise ratio (PSNR), the structural similarity index (SSIM), as well as either the mean squared error (MSE) with respect to the PK parameters, calculated for the fully sampled DCE-MRI sequences, or the segmentation compatibility, measured in terms of Dice scores and Hausdorff distance. The code is available on GitHub."
featured: false
publication: "*Medical Image Analysis*"
tags: ["Deep learning", "GANs", "K-space subsampling", "MRI reconstruction"]
url_pdf: "https://www.sciencedirect.com/science/article/pii/S1361841520301110"
doi: "10.1016/j.media.2020.101747"
---


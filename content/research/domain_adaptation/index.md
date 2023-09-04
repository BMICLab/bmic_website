---
title: Domain Adaptation 
summary: Bridging the domain gap in medical imaging using hypernetworks
author: admin
tags:
  - MRI
  - Hypernetworks
  - Domain adaptation
date: '2023-09-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Block diagram of proposed method
  focal_point: Smart

links:
url_code: 'https://github.com/doronser/mri_uda'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---

## Domain Adaptation in Medical Imaging
One of the main challenges in bringing deep learning models to production is the domain gap between training data and test data. This domain shift is even more significant in medical imaging, where the training data is often collected from different scanners, with different protocols, and different populations.

Domain adaptation is the task of mitigating the domain shift using various methods. In this work, we propose a novel domain adaptation method for medical imaging, which is based on hypernetworks. Hypernetworks are a class of neural networks that generate the weights of another network, called the main network. We show that the input data can be used to generate domain-specific embeddings, which when input to a hypernetwork, can be used to generate domain-specific classification layers.

We also show that given a diverse enough set of training domains, the hypernetwork can succesfully generalize to unseen datasets, since the obtained domain embeddings can be expressed as a linear combination of existing domains.

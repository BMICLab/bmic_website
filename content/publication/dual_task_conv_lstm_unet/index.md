---
title: 'Dual-Task ConvLSTM-UNet for Instance Segmentation of Weakly Annotated Microscopy Videos'
authors:
  - shaked0
  - tammy
#author_notes:
date: '2018-08-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'IEEE Transactions on Medical Imaging'
publication_short: 'IEEE TMI'

abstract: Convolutional Neural Networks (CNNs) are considered state of the art segmentation methods for biomedical images in general and microscopy sequences of living cells, in particular. The success of the CNNs is attributed to their ability to capture the structural properties of the data, which enables accommodating complex spatial structures of the cells, low contrast, and unclear boundaries. However, in their standard form CNNs do not exploit the temporal information available in time-lapse sequences, which can be crucial to separating touching and partially overlapping cell instances. In this work, we exploit cell dynamics using a novel CNN architecture which allows multi-scale spatio-temporal feature extraction. Specifically, a novel recurrent neural network (RNN) architecture is proposed based on the integration of a Convolutional Long Short Term Memory (ConvLSTM) network with the U-Net. The proposed ConvLSTM-UNet network is constructed as a dual-task network to enable training with weakly annotated data, in the form of approximate cell centers, termed markers, when the complete cells’ outlines are not available. We further use the fast marching method to facilitate the partitioning of clustered cells into individual connected components. Finally, we suggest an adaptation of the method for 3D microscopy sequences without drastically increasing the computational load. The method was evaluated on the Cell Segmentation Benchmark and was ranked among the top three methods on six submitted datasets. Exploiting the proposed built-in marker estimator we also present state-of-the-art cell detection results for an additional, publicly available, weekly annotated dataset. The source code is available at https://gitlab.com/shaked0/lstmUnet 

# Summary. An optional shortened abstract.
summary:  In this work, we exploit cell dynamics using a novel CNN architecture which allows multi-scale spatio-temporal feature extraction. Specifically, a novel recurrent neural network (RNN) architecture is proposed based on the integration of a Convolutional Long Short Term Memory (ConvLSTM) network with the U-Net. The proposed ConvLSTM-UNet network is constructed as a dual-task network to enable training with weakly annotated data, in the form of approximate cell centers, termed markers, when the complete cells’ outlines are not available.

tags:
  - Cell segmentation
  - Weakly supervised learning
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/9717246
url_code: 'https://github.com/shakedCohen11/dual_task_convlstm_unet'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Model architecture'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

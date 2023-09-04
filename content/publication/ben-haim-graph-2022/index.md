---
title: "Graph Neural Network for Cell Tracking in Microscopy Videos"
date: 2022-07-01
publishDate: 2023-09-04T14:13:46.269928Z
authors: ["Tal Ben-Haim", "Tammy Riklin Raviv"]
publication_types: ["0"]
abstract: "We present a novel graph neural network (GNN) approach for cell tracking in high-throughput microscopy videos. By modeling the entire time-lapse sequence as a direct graph where cell instances are represented by its nodes and their associations by its edges, we extract the entire set of cell trajectories by looking for the maximal paths in the graph. This is accomplished by several key contributions incorporated into an end-to-end deep learning framework. We exploit a deep metric learning algorithm to extract cell feature vectors that distinguish between instances of different biological cells and assemble same cell instances. We introduce a new GNN block type which enables a mutual update of node and edge feature vectors, thus facilitating the underlying message passing process. The message passing concept, whose extent is determined by the number of GNN blocks, is of fundamental importance as it enables the `flow' of information between nodes and edges much behind their neighbors in consecutive frames. Finally, we solve an edge classification problem and use the identified active edges to construct the cells' tracks and lineage trees. We demonstrate the strengths of the proposed cell tracking approach by applying it to 2D and 3D datasets of different cell types, imaging setups, and experimental conditions. We show that our framework outperforms current state-of-the-art methods on most of the evaluated datasets. The code is available at our repository: https://github.com/talbenha/cell-tracker-gnn."
featured: false
publication: "*arXiv*"
tags: ["Computer Science - Computer Vision and Pattern Recognition"]
url_pdf: "http://arxiv.org/abs/2202.04731"
---


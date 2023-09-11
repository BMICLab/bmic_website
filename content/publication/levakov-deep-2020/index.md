---
title: "From a deep learning model back to the brain—Identifying regional predictors and their relation to aging"
date: 2020-01-01
publishDate: 2023-09-04T14:40:57.581926Z
authors: ["Gidon Levakov", "Gideon Rosenthal", "Ilan Shelef", "Tammy Riklin Raviv", "Galia Avidan"]
publication_types: ["2"]
abstract: "We present a Deep Learning framework for the prediction of chronological age from structural magnetic resonance imaging scans. Previous findings associate increased brain age with neurodegenerative diseases and higher mortality rates. However, the importance of brain age prediction goes beyond serving as biomarkers for neurological disorders. Specifically, utilizing convolutional neural network (CNN) analysis to identify brain regions contributing to the prediction can shed light on the complex multivariate process of brain aging. Previous work examined methods to attribute pixel/voxel-wise contributions to the prediction in a single image, resulting in “explanation maps” that were found noisy and unreliable. To address this problem, we developed an inference scheme for combining these maps across subjects, thus creating a population-based, rather than a subject-specific map. We applied this method to a CNN ensemble trained on predicting subjects' age from raw T1 brain images in a lifespan sample of 10,176 subjects. Evaluating the model on an untouched test set resulted in mean absolute error of 3.07 years and a correlation between chronological and predicted age of r = 0.98. Using the inference method, we revealed that cavities containing cerebrospinal fluid, previously found as general atrophy markers, had the highest contribution for age prediction. Comparing maps derived from different models within the ensemble allowed to assess differences and similarities in brain regions utilized by the model. We showed that this method substantially increased the replicability of explanation maps, converged with results from voxel-based morphometry age studies and highlighted brain regions whose volumetric variability correlated the most with the prediction error."
featured: false
publication: "*Human Brain Mapping*"
tags: ["brain aging", "convolutional neural networks", "deep learning", "interpretability", "neuroimaging"]
url_pdf: "https://onlinelibrary.wiley.com/doi/abs/10.1002/hbm.25011"
doi: "10.1002/hbm.25011"
---


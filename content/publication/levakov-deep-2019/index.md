---
title: "From a deep learning model back to the brain - inferring morphological markers and their relation to aging"
date: 2019-11-01
publishDate: 2023-09-04T14:40:54.723991Z
authors: ["Gidon Levakov", "Gideon Rosenthal", "Ilan Shelef", "Tammy Riklin Raviv", "Galia Avidan"]
publication_types: ["0"]
abstract: "We present a Deep Learning framework for the prediction of chronological age from structural MRI scans. Previous findings associate an overestimation of brain age with neurodegenerative diseases and higher mortality rates. However, the importance of brain age prediction goes beyond serving as biomarkers for neurological disorders. Specifically, utilizing convolutional neural network (CNN) analysis to identify brain regions contributing to the prediction can shed light on the complex multivariate process of brain aging. Previous work examined methods to attribute pixel/voxel-wise contributions to the prediction in a single image, resulting in ‘explanation maps’ that were found noisy and unreliable. To address this problem, we developed an inference framework for combining these maps across subjects, thus creating a population-based rather than a subject-specific map. We applied this method to a CNN ensemble trained on predicting subjects’ age from raw T1 brain images of 10,176 subjects. Evaluating the model on an untouched test set resulted in mean absolute error of 3.07 years and a correlation between chronological and predicted age of r=0.98. Using the inference method, we revealed that cavities containing CSF, previously found as general atrophy markers, had the highest contribution for age prediction. Comparing maps derived from different models within the ensemble allowed to assess differences and similarities in brain regions utilized by the model. We showed that this method substantially increased the replicability of explanation maps, converged with results from voxel-based morphometry age studies and highlighted brain regions whose volumetric variability contributed the most to the prediction. HighlightsCNNs ensemble is shown to estimate “brain age” from sMRI with an MAE of ∼3.1 yearsA novel framework enables to highlight brain regions contributing to the predictionThis framework results in explanation maps showing consistency with the literatureAs sample size increases, these maps show higher inter-sample replicabilityCSF cavities reflecting general atrophy were found as a prominent aging biomarker"
featured: false
publication: "*bioRxiv*"
url_pdf: "https://www.biorxiv.org/content/10.1101/803742v2"
doi: "10.1101/803742"
---


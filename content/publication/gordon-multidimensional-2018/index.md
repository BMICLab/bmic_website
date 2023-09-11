---
title: "Multidimensional co-segmentation of longitudinal brain MRI ensembles in the presence of a neurodegenerative process"
date: 2018-09-01
publishDate: 2023-09-04T14:40:51.289073Z
authors: ["Shiri Gordon", "Irit Dolgopyat", "Itamar Kahn", "Tammy Riklin Raviv"]
publication_types: ["2"]
abstract: "MRI Segmentation of a pathological brain poses a significant challenge, as the available anatomical priors that provide top-down information to aid segmentation are inadequate in the presence of abnormalities. This problem is further complicated for longitudinal data capturing impaired brain development or neurodegenerative conditions, since the dynamic of brain atrophies has to be considered as well. For these cases, the absence of compatible annotated training examples renders the commonly used multi-atlas or machine-learning approaches impractical. We present a novel segmentation approach that accounts for the lack of labeled data via multi-region multi-subject co-segmentation (MMCoSeg) of longitudinal MRI sequences. The underlying, unknown anatomy is learned throughout an iterative process, in which the segmentation of a region is supported both by the segmentation of the neighboring regions, which share common boundaries, and by the segmentation of corresponding regions, in the other jointly segmented images. A 4D multi-region atlas that models the spatio-temporal deformations and can be adapted to different subjects undergoing similar degeneration processes is reconstructed concurrently. An inducible mouse model of p25 accumulation (the CK-p25 mouse) that displays key pathological hallmarks of Alzheimer disease (AD) is used as a gold-standard to test the proposed algorithm by providing a conditional control of rapid neurodegeneration. Applying the MMCoSeg to a cohort of CK-p25 mice and littermate controls yields promising segmentation results that demonstrate high compatibility with expertise manual annotations. An extensive comparative analysis with respect to current well-established, atlas-based segmentation methods highlights the advantage of the proposed approach, which provides accurate segmentation of longitudinal brain MRIs in pathological conditions, where only very few annotated examples are available."
featured: false
publication: "*NeuroImage*"
tags: ["Brain atrophies", "Level sets method", "Longitudinal data", "Mouse brain MRI", "Multi-region co-segmentation", "Neurodegenerative conditions"]
url_pdf: "https://www.sciencedirect.com/science/article/pii/S1053811918303495"
doi: "10.1016/j.neuroimage.2018.04.039"
---


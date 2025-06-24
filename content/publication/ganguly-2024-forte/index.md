---
title: '[ICLR] Forte: Finding Outliers with Representation Typicality Estimation'
authors:
- Debargha Ganguly
- Warren Morningstar
- Andrew Yu
- Vipin Chaudhary
date: '2025-01-22T00:00:00Z'
publishDate: '2025-06-24T13:45:36.292447Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2410.01322*'
abstract: Generative models can now produce photorealistic synthetic data which is virtually indistinguishable from the real data used to train it. This is a significant evolution over previous models which could produce reasonable facsimiles of the training data, but ones which could be visually distinguished from the training data by human evaluation. Recent work on OOD detection has raised doubts that generative model likelihoods are optimal OOD detectors due to issues involving likelihood misestimation, entropy in the generative process, and typicality. We speculate that generative OOD detectors also failed because their models focused on the pixels rather than the semantic content of the data, leading to failures in near-OOD cases where the pixels may be similar but the information content is significantly different. We hypothesize that estimating typical sets using self-supervised learners leads to better OOD detectors. We introduce a novel approach that leverages representation learning, and informative summary statistics based on manifold estimation, to address all of the aforementioned issues. Our method outperforms other unsupervised approaches and achieves state-of-the art performance on well-established challenging benchmarks, and new synthetic data detection tasks.
Summary: Out-of-distribution detection using self-supervised learners
featured: true
url_pdf: 'https://arxiv.org/pdf/2410.01322'
url_code: 'https://github.com/DebarghaG/forte'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://iclr.cc/virtual/2025/poster/30817'
# url_video: 'https://youtube.com'
---

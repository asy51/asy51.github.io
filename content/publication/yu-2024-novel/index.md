---
title: 'Novel adaptation of video segmentation to 3D MRI: efficient zero-shot knee
  segmentation with SAM2'
authors:
- Andrew Seohwan Yu
- Mohsen Hariri
- Xuecen Zhang
- Mingrui Yang
- Vipin Chaudhary
- Xiaojuan Li
date: '2024-01-01T00:00:00Z'
publishDate: '2025-06-24T13:45:36.307767Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2408.04762*'
abstract: Intelligent medical image segmentation methods are rapidly evolving and being increasingly applied, yet they face the challenge of domain transfer, where algorithm performance degrades due to different data distributions between source and target domains. To address this, we introduce a method for zero-shot, single-prompt segmentation of 3D knee MRI by adapting Segment Anything Model 2 (SAM2), a general-purpose segmentation model designed to accept prompts and retain memory across frames of a video. By treating slices from 3D medical volumes as individual video frames, we leverage SAM2's advanced capabilities to generate motion- and spatially-aware predictions. We demonstrate that SAM2 can efficiently perform segmentation tasks in a zero-shot manner with no additional training or fine-tuning, accurately delineating structures in knee MRI scans using only a single prompt. Our experiments on the Osteoarthritis Initiative Zuse Institute Berlin (OAI-ZIB) dataset reveal that SAM2 achieves high accuracy on 3D knee bone segmentation, with a testing Dice similarity coefficient of 0.9643 on tibia. We also present results generated using different SAM2 model sizes, different prompt schemes, as well as comparative results from the SAM1 model deployed on the same dataset. This breakthrough has the potential to revolutionize medical image analysis by providing a scalable, cost-effective solution for automated segmentation, paving the way for broader clinical applications and streamlined workflows.
Summary: Zero-shot segmentation of knee MRI using SAM2, adapting video capabilities for 3D
featured: true
url_pdf: 'https://arxiv.org/pdf/2408.04762'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://doi.org/10.1117/12.3047346'
# url_video: 'https://youtube.com'
---

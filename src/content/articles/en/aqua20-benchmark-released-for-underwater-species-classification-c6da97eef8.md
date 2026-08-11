---
decisionKey: "c6da97eef84925f0d68afb7616e631e3a2e492f007dc03277ff6e33cb96c780b"
language: "en"
title: "AQUA20 Benchmark Released for Underwater Species Classification"
summary: "AQUA20, a benchmark dataset of 8,171 underwater images across 20 marine species, is introduced with a 13-model evaluation in which ConvNeXt achieves the best reported accuracy. The benchmark targets realistic challenges including illumination, turbidity, and occlusion."
publishedAt: "2026-08-11T18:46:48.986Z"
score: 0.86
topics:
  - "Computer Vision"
  - "Benchmark Dataset"
  - "Underwater Species Classification"
topicIds:
  - "computer-vision-ykrxu8"
  - "benchmark-dataset-tydhb8"
  - "underwater-species-classification-xrneou"
sourceUrls:
  - "https://arxiv.org/abs/2506.17455"
---

The authors present AQUA20 as a benchmark dataset for underwater species classification under challenging visual conditions. The dataset contains 8,171 images spanning 20 marine species and is designed to reflect issues such as illumination, turbidity, and occlusion. The study compares 13 deep learning architectures, including lightweight CNNs (SqueezeNet, MobileNetV2) and transformer-based models (ViT, ConvNeXt). The source is an arXiv listing with a journal reference shown; full peer-review details are not supplied.

In the authors' evaluation on AQUA20, ConvNeXt achieved the best Top-3 accuracy of 98.82%, Top-1 accuracy of 90.69%, and overall F1-score of 88.92%. The paper also reports GRAD-CAM and LIME explainability analyses to interpret model strengths and failure modes.

The abstract does not provide per-class image counts, image provenance, or label-quality assessment for AQUA20. Evaluation metrics are reported as aggregates without confidence intervals or significance tests, so the size of the ConvNeXt performance gap over other models is not statistically quantified.

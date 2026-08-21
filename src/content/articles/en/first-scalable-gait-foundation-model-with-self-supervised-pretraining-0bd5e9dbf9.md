---
decisionKey: "0bd5e9dbf90ddcee0edc9c3886471e40dcc2350edbefaa7d993a77c92e49f2e8"
language: "en"
title: "First Scalable Gait Foundation Model with Self-Supervised Pretraining"
summary: "Researchers introduce FoundationGait, a scalable self-supervised pretraining framework trained on over 2 million walking sequences from 12 public gait datasets, achieving zero-shot performance across datasets and tasks."
publishedAt: "2026-08-21T14:06:18.549Z"
score: 0.92
topics:
  - "Computer Vision"
  - "Foundation Models"
  - "Gait Recognition"
topicIds:
  - "computer-vision-ykrxu8"
  - "foundation-models-29zx6m"
  - "gait-recognition-19d2ozz"
sourceUrls:
  - "https://arxiv.org/abs/2512.00691"
---

Gait recognition is a biometric technique in computer vision for identifying individuals, but existing methods often struggle with generalization across datasets and tasks. To address this, researchers propose FoundationGait, described as the first scalable self-supervised pretraining framework for gait understanding. Its largest version has nearly 0.13 billion parameters and is pretrained on 12 public gait datasets comprising over 2 million walking sequences.

In zero-shot evaluation, FoundationGait achieves 48.0% rank-1 accuracy on the Gait3D dataset (1,000 test subjects) and 64.5% on the OU-MVLP dataset (more than 5,000 test subjects). Additionally, it performs robustly across a wide spectrum of gait datasets, conditions (e.g., cross-view, cross-walking), and tasks (including human identification, scoliosis screening, depression prediction, and attribute estimation), whether fine-tuned or not.

The paper is an arXiv preprint and has not been peer-reviewed. The abstract does not provide baseline comparisons or detailed experimental setup, so the superiority over existing methods is not fully quantified here.

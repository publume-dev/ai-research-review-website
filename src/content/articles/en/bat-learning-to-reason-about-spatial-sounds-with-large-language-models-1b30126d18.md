---
decisionKey: "1b30126d188822dfd741e49ff0f817eba691696548e75793749b40314ca42b09"
language: "en"
title: "BAT: Learning to Reason about Spatial Sounds with Large Language Models"
summary: "BAT integrates a binaural acoustic scene analysis model with a large language model to enable spatial sound reasoning; the authors also introduce SpatialSoundQA, a spatial-sound question-answering dataset."
publishedAt: "2026-08-18T03:10:36.725Z"
score: 0.82
topics:
  - "AI Research"
  - "Audio"
  - "Machine Learning"
topicIds:
  - "ai-research-10iv84k"
  - "audio-1q99m6x"
  - "machine-learning-168tuwc"
sourceUrls:
  - "https://arxiv.org/abs/2402.01591"
---

Spatial sound reasoning involves understanding sound events and their spatial properties (such as direction and distance), which is critical for robotics and auditory assistance systems. Existing models usually address sound event detection and spatial localization separately, while BAT aims to integrate binaural acoustic scene analysis with a large language model to achieve unified reasoning.

BAT uses a binaural acoustic scene analysis model (Spatial-AST) as its front end integrated with the LLaMA-2 7B large language model to perform spatial sound reasoning. The authors synthesized a binaural audio dataset using AudioSet and SoundSpaces 2.0, and developed SpatialSoundQA, a spatial-sound question-answering dataset. Spatial-AST demonstrates strong performance on sound event detection, spatial localization, and distance estimation.

The abstract does not provide specific quantitative results or benchmark comparisons, so the claimed superior performance is not verified with data.

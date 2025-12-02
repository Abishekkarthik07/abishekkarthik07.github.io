---
layout: single
title: "Multi Head Attention Enhanced Inception v3 for Cardiomegaly Detection"
permalink: /publication/2025-cardiomegaly/
author_profile: true
---

## Abstract

This research presents a multi-head-attention enhanced Inception v3 system for cardiomegaly detection using chest X-ray imaging. The model combines convolutional feature extraction with spatial attention to prioritize diagnostically significant anatomical areas, enabling reliable disease detection.

## Motivation / Problem

Manual screening for heart enlargement requires specialist expertise and suffers inter-reader variability. Automated systems must address low-contrast images and overlapping anatomical structures to reliably detect cardiomegaly.

## Method / Approach

We enhance Inception v3 with a multi-head spatial attention module that re-weights convolutional feature maps to amplify diagnostically relevant regions. A careful preprocessing pipeline and balanced training augmentations improve robustness. Evaluation includes precision, recall, and AUC metrics.

## Results

- Accuracy: 95.6%
- AUC: 96%

## My Role

I developed the attention integration block, optimized the training pipeline, and performed hyperparameter tuning and attention-heatmap visualizations to validate model focus.

---

[Paper](https://arxiv.org/abs/2511.20101)

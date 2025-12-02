---
layout: single
title: "Hybrid Convolution Neural Network Integrated with Pseudo-Newton Boosting for Lumbar Spine Degeneration Detection"
permalink: /publication/2025-spine/
author_profile: true
---

## Abstract

This paper proposes an enhanced hybrid deep learning framework for lumbar spine degeneration classification using DICOM image data, combining EfficientNet and VGG19 with a novel Pseudo-Newton Boosting layer and a sparsity-induced feature-reduction layer. The model achieved significant improvement over baseline architectures with 88.1% accuracy.

## Motivation / Problem

Subtle pathological variations in spinal degeneration are difficult to isolate, and high-dimensional DICOM features often introduce redundancy that hinders efficient learning. Reliable automated tools are needed to support radiologists and reduce diagnostic variability.

## Method / Approach

We combine EfficientNet and VGG19 backbones with a Pseudo-Newton Boosting dynamic weight refinement layer. A sparsity-induced feature reduction layer removes redundant features to focus learning capacity on informative patterns. The pipeline includes advanced preprocessing of DICOM images and stratified evaluation.

## Results

- Precision: 0.90
- Recall: 0.861
- F1: 0.88
- Loss: 0.18
- Accuracy: 88.1%

## My Role

I implemented the pseudo-Newton update algorithm and coordinated the fusion of the hybrid architecture. I designed evaluation experiments with metric analysis and carried out model reduction for faster inference.

---

[Paper](https://arxiv.org/abs/2511.13877)

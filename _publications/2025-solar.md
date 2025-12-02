---
layout: single
title: "Unified Deep Learning Platform for Dust and Fault Diagnosis in Solar Panels Using Thermal and Visual Imaging"
permalink: /publication/2025-solar/
author_profile: true
---

## Abstract

This study introduces a unified deep learning platform enabling automated dust detection and fault diagnosis using thermal and visual imaging. Combining CNN-ResNet and KerNet attention models, the system identifies panel defects and efficiency-reducing debris under practical environmental variability. Results demonstrate significant diagnostic improvement compared to traditional camera-based inspection workflows.

## Motivation / Problem

Solar farms experience energy loss due to undetected faults and dust accumulation; manual inspection is slow, costly, and error-prone. Automated, multi-modal inspection improves reliability and reduces maintenance overhead for large-scale solar installations.

## Method / Approach

We construct a dual-domain dataset (thermal + RGB) and implement a hybrid ResNet + KerNet architecture with multi-attention fusion to combine thermal and visual cues. Preprocessing includes gamma correction and Gaussian filtering. The platform performs combined defect segmentation and classification with post-processing to prioritize repair actions.

## Results

- Accuracy: 95–97% across test splits
- Reduced time-to-detection and improved reliability over standard visual inspection

## My Role

I engineered the preprocessing pipeline and implemented the multi-attention fusion supporting thermal–visual feature integration. I conducted comparative evaluation experiments and built an inference visualization dashboard to assist operations teams.

---

[Paper](https://arxiv.org/abs/2511.18514)

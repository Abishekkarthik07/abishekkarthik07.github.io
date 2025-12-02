---
layout: single
title: "Revolutionizing Glioma Segmentation and Grading Using 3D MRI-Guided Hybrid Deep Learning Models"
permalink: /publication/2025-glioma/
author_profile: true
---

## Abstract

Gliomas are aggressive brain tumors requiring precise and early diagnosis. This research introduces a hybrid deep learning model integrating U-Net-based 3D segmentation and a DenseNet-VGG hybrid classification network with spatial–channel multi-head attention. Preprocessed 3D MRI is segmented to isolate tumor regions, followed by classification using combined feature attention. The system achieved a Dice coefficient of 98% for segmentation and a classification accuracy of 99%, outperforming conventional deep learning approaches and improving diagnosis reliability.

## Motivation / Problem

Glioma segmentation suffers from high spatial complexity, varying tumor morphology, and scarcity of annotated 3D MRI datasets. Traditional CNN models fail to capture long-range dependencies and intra-tumor structural variations. Clinical workflows require interpretable results, yet most models lack transparent decision pathways needed for surgeon trust and treatment planning.

## Method / Approach

We employ a 3D U-Net for volumetric segmentation to localize tumor regions precisely. A hybrid DenseNet-VGG classifier ingests segmentation outputs and multi-scale features, augmented by spatial and channel attention modules to emphasize clinically relevant structures. Preprocessing includes intensity normalization, resampling to uniform voxel spacing, and data augmentation (rotations, elastic transforms). Evaluation uses multi-metric validation including Dice, IoU, precision, recall, and F1.

## Results

- Dice Coefficient: 98%
- Classification Accuracy: 99%
- Outperforms baseline U-Net and transformer-free CNN solutions
- Improved interpretability via attention heatmaps aiding clinical validation

## My Role

I implemented and optimized the hybrid attention-enhanced DenseNet-VGG architecture and coordinated the segmentation-classification pipeline. I engineered MRI preprocessing transformations and tuned model parameters for 3D medical imaging conditions. I led evaluation experiments, visualizations, interpretability heat-maps, and ablation analyses demonstrating the effectiveness of attention modules.

---

[Paper](https://arxiv.org/abs/2511.21673)

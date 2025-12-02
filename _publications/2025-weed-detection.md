---
layout: single
title: "A Hybrid CNN–ViT–GNN Framework with GAN-Based Augmentation for Intelligent Weed Detection in Precision Agriculture"
permalink: /publication/2025-weed-detection/
author_profile: true
---

## Abstract

Weed detection is an essential component in precision agriculture as accurate species identification enables selective herbicide application and supports sustainable crop management. This work proposes a hybrid deep learning framework integrating Convolutional Neural Networks (CNNs), Vision Transformers (ViTs), and Graph Neural Networks (GNNs) to ensure strong generalization in diverse field environments. A GAN-based augmentation method is introduced to balance class distributions and improve robustness, supported by self-supervised contrastive pre-training to extract features from limited annotated datasets. Experimental evaluation demonstrates 99.33% accuracy, precision, and recall across multiple benchmark datasets, outperforming traditional models. The proposed hybrid architecture achieves superior interpretability and deploys efficiently on edge devices, making real-time weed detection feasible.

## Motivation / Problem

Existing weed detection models struggle to generalize across the extreme variability encountered in real fields — lighting, soil, occlusion, and species morphology vary widely. Class imbalance further undermines performance, and single-architecture CNNs often cannot capture both fine-grained local texture and broad contextual relationships. A scalable, interpretable, and edge-deployable solution is therefore critical to reduce herbicide use and enable automated crop management.

## Method / Approach

We design a hierarchical pipeline that fuses CNNs (for local texture), ViTs (for global context), and a GNN (to model relationships between plant instances). A GAN-based augmentation strategy synthesizes diverse, realistic examples to address class imbalance. Contrastive self-supervised pre-training is applied to improve representations from limited labeled data. The overall model is optimized for low-latency inference and quantized for edge deployment. Training uses field-acquired datasets with stratified cross-validation and extensive ablation studies to validate each component.

## Results

- Accuracy: 99.33%
- Precision: 99.33%
- Recall: 99.33%
- F1-score: 99.33%
- Robust performance across varying environmental conditions and superior results compared to baseline CNN architectures

## My Role

I led the architecture design and integration, implementing the CNN–ViT–GNN fusion and engineering the GAN-based augmentation pipeline. I developed the contrastive pre-training workflow, coordinated dataset collection and preprocessing, performed ablation studies and hyperparameter optimization, and implemented edge-inference optimizations to achieve real-time performance.

---

[Paper](https://arxiv.org/abs/2511.15535)  
[Acceptance Letter](/files/Acceptance Letter ICACRS076.pdf)

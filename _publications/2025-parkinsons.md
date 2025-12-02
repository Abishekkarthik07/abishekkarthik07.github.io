---
layout: single
title: "A Novel CustNetGC Boosted Model with Spectral Features for Parkinson's Disease Prediction"
permalink: /publication/2025-parkinsons/
author_profile: true
---

## Abstract

This research explores Parkinson's disease (PD) detection using voice signals via a hybrid CNN with Grad-CAM interpretability and CatBoost classification. Spectral audio features are extracted using harmonic-percussive source separation, enabling accurate and interpretable speech-based diagnosis.

## Motivation / Problem

Clinical neurological testing for PD is resource-intensive and may not scale for large populations. Speech-based screening offers a low-cost, non-invasive alternative, but models must be both accurate and interpretable to gain clinical acceptance.

## Method / Approach

We extract HPSS-based spectral representations and construct a CNN feature extractor whose activations are interpreted with Grad-CAM. A CatBoost classifier ingests the learned representations for robust final prediction. Ablation studies evaluate spectral slope and harmonic features.

## Results

- Accuracy: 99.06%
- Strong interpretability via Grad-CAM highlighting neuromuscular speech deviations

## My Role

I developed the acoustic processing pipeline, designed spectral feature extraction, applied Grad-CAM-based localization, and performed model tuning and ROC-AUC analysis to validate performance.

---

[Paper](https://arxiv.org/abs/2511.15485)

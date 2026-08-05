---
title: "Semi-Supervised Cardiac MRI Segmentation"
excerpt: "A computationally efficient dual-decoder U-Net for 3D cardiac MRI segmentation, trained with limited labeled data."
collection: portfolio
date: 2022-09-01
header:
  image: projects/cardiac-mri-segmentation.svg
  teaser: projects/cardiac-mri-segmentation.svg
tags:
  - Medical Imaging
  - Semi-Supervised Learning
  - PyTorch
---

Manually segmenting cardiac structures in MRI scans is slow and expert-dependent, and labeled data is scarce relative to how much unlabeled scan data exists. As a Research Associate in LUMS's ATP Lab, I worked on closing that gap for 3D cardiac MRI.

**Architecture.** I designed a computationally efficient U-Net with two decoders, where the disagreement between decoder predictions on unlabeled data acts as a learning signal — letting the model benefit from scans that were never manually annotated.

**Pipeline.** I built the complete pipeline end to end: preprocessing, semi-supervised training, and evaluation, across both 2D and 3D cardiac MRI datasets, in PyTorch.

**Generalization.** To help the model hold up across scanners and sites, I explored self-supervised pretraining and fine-tuning strategies aimed specifically at generalizing across multi-center medical datasets — a common failure point for models trained on a single hospital's data.

**Result.** The approach achieved state-of-the-art performance on public cardiac MRI segmentation benchmarks while keeping computational cost low enough to be practical.

---
title: Remote Sensing Segmentation with Partial Labels
date: 2025-05-15
links:
  - type: github
    url: https://github.com/Abdullah-Bin-Naeem/Remote-Sensing-Image-Segmentation-with-Partially-annotated-labels
tags:
  - Computer Vision
  - Semantic Segmentation
  - Remote Sensing
---

A semantic segmentation model for remote sensing images trained with sparse (point-based) annotations. This project uses a ResNet18-based architecture and a custom Partial Cross Entropy (CE) Loss to effectively train on the ISPRS Potsdam dataset with only 22.2% of pixels labeled, reducing the need for dense, pixel-wise ground truth.

- Implemented a custom Partial Cross Entropy Loss function with a focal parameter (γ=2) to train a segmentation model using only sparse point annotations (20,000 points per image).
- Leveraged a ResNet18 encoder with a custom decoder and frequency-based class weights to address significant class imbalance in the ISPRS Potsdam dataset.
- Achieved 65.7% mIoU, a significant improvement over the 58.3% mIoU baseline without class weights, demonstrating the effectiveness of the partial-label approach.
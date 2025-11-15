---
title: BuduNet — Dual-Task Segmentation for Autonomous Driving
date: 2024-02-10
links:
  - type: github
    url: https://github.com/Abdullah-Bin-Naeem
tags:
  - Computer Vision
  - Autonomous Driving
  - Segmentation
---

BuduNet blends ideas from YOLOP and TwinLiteNet, pairing a single decoder with twin heads for drivable-area and lane segmentation. The model uses ResNet-50 as a backbone, supports real-time inference, and was trained/benchmarked on BDD100K.

<!--more-->

- Implemented custom multi-task loss that balances lane continuity with surface coverage.
- Achieved stable 40+ FPS inference on desktop GPUs and pruned variants for Jetson deployment.
- Released experiment tracking scripts, data configs, and ONNX export helpers for easy reuse.

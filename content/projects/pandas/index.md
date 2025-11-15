---
title: EcoDrive — Autonomous Waste Collection Car
date: 2024-04-15
links:
  - type: github
    url: https://github.com/Abdullah-Bin-Naeem
tags:
  - Robotics
  - Reinforcement Learning
  - Smart Cities
---

Proof-of-concept autonomous car that responds to smart-bin signals to optimize city waste collection. EcoDrive runs on an NVIDIA Jetson Nano, fusing perception and planning through PPO/SAC agents trained inside CARLA and Donkey Car simulators with camera-only inputs.

<!--more-->

- Designed adaptive routing that balances fill-level priority, travel time, and safety.
- Implemented on-vehicle semantic segmentation for bin detection plus MQTT telemetry for dispatch.
- Validated the policy in simulation before deploying to a scaled hardware prototype for live demos.

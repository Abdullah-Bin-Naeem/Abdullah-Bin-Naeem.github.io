---
title: 'FACT++: Multi-Stage Hand Keypoint Fusion for Enhanced Egocentric Action Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes: []

date: '2025-02-15T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE 4th International Conference on Computing and Machine Intelligence (ICMI 2025)*
publication_short: In *ICMI 2025*

abstract: |
  FACT++ introduces multi-stage fusion of egocentric hand keypoints to dramatically improve action segmentation in first-person videos. By coupling geometric priors with lightweight temporal reasoning, the method achieves 86.3% average accuracy on the GTEA dataset (88.6% on Split 1, 87.01% on Split 2), surpassing prior state-of-the-art approaches while remaining deployable on edge hardware.

# Summary. An optional shortened abstract.
summary: FACT++ fuses egocentric hand keypoints across stages to set a new SOTA on GTEA (86.3% avg. accuracy) with an edge-ready architecture.

tags:
  - Computer Vision
  - Egocentric Action Recognition
  - Robotics

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids: {}

# Custom links
links:
  - type: code
    url: https://github.com/Abdullah-Bin-Naeem

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

FACT++ demonstrates how explicit modeling of hand-object interactions can simplify downstream action segmentation. After curating high-quality keypoint tracks, we apply staged fusion (per-frame, temporal, semantic) to capture intent, then distill the pipeline into a lightweight decoder that generalizes across wearers. The approach provides interpretable attention maps for human factors teams and remains compatible with embedded NVIDIA Jetson deployments used in EcoDrive.

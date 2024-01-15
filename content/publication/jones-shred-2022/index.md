---
title: 'SHRED: 3D Shape Region Decomposition with Learned Local Operations'
authors:
- R. Kenny Jones
- Aalia Habib
- Daniel Ritchie
date: '2022-10-01'
publishDate: '2024-01-15T06:08:03.643574Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'We present SHRED, a method for 3D SHape REgion Decomposition. SHRED takes
  a 3D point cloud as input and uses learned local operations to produce a segmentation
  that approximates fine-grained part instances. We endow SHRED with three decomposition
  operations: splitting regions, fixing the boundaries between regions, and merging
  regions together. Modules are trained independently and locally, allowing SHRED
  to generate high-quality segmentations for categories not seen during training.
  We train and evaluate SHRED with fine-grained segmentations from PartNet; using
  its mergethreshold hyperparameter, we show that SHRED produces segmentations that
  better respect ground-truth annotations compared with baseline methods, at any desired
  decomposition granularity. Finally, we demonstrate that SHRED is useful for downstream
  applications, out-performing all baselines on zero-shot fine-grained part instance
  segmentation and few-shot finegrained semantic segmentation when combined with methods
  that learn to label shape regions. CCS Concepts: • Computing methodologies → Shape
  analysis; Neural networks.'
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
- Computer Science - Graphics
links:
- name: URL
  url: http://arxiv.org/abs/2206.03480
---

---
title: 'Wonder3D: Single Image to 3D using Cross-Domain Diffusion'
authors:
- Xiaoxiao Long
- Yuan-Chen Guo
- Cheng Lin
- Yuan Liu
- Zhiyang Dou
- Lingjie Liu
- Yuexin Ma
- Song-Hai Zhang
- Marc Habermann
- Christian Theobalt
- Wenping Wang
date: '2023-11-01'
publishDate: '2024-01-15T06:08:03.988563Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: In this work, we introduce Wonder3D, a novel method for efficiently generating
  high-fidelity textured meshes from single-view images.Recent methods based on Score
  Distillation Sampling (SDS) have shown the potential to recover 3D geometry from
  2D diffusion priors, but they typically suffer from time-consuming per-shape optimization
  and inconsistent geometry. In contrast, certain works directly produce 3D information
  via fast network inferences, but their results are often of low quality and lack
  geometric details. To holistically improve the quality, consistency, and efficiency
  of image-to-3D tasks, we propose a cross-domain diffusion model that generates multi-view
  normal maps and the corresponding color images. To ensure consistency, we employ
  a multi-view cross-domain attention mechanism that facilitates information exchange
  across views and modalities. Lastly, we introduce a geometry-aware normal fusion
  algorithm that extracts high-quality surfaces from the multi-view 2D representations.
  Our extensive evaluations demonstrate that our method achieves high-quality reconstruction
  results, robust generalization, and reasonably good efficiency compared to prior
  works.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2310.15008
---

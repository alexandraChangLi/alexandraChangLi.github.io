---
title: 'GrowSP: Unsupervised Semantic Segmentation of 3D Point Clouds'
authors:
- Zihui Zhang
- Bo Yang
- Bing Wang
- Bo Li
date: '2023-06-01'
publishDate: '2024-01-15T06:08:03.612952Z'
publication_types:
- paper-conference
publication: '*2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition
  (CVPR)*'
doi: 10.1109/CVPR52729.2023.01690
abstract: We study the problem of 3D semantic segmentation from raw point clouds.
  Unlike existing methods which primarily rely on a large amount of human annotations
  for training neural networks, we propose the first purely unsupervised method, called
  GrowSP, to successfully identify complex semantic classes for every point in 3D
  scenes, without needing any type of human labels or pretrained models. The key to
  our approach is to discover 3D semantic elements via progressive growing of superpoints.
  Our method consists of three major components, 1) the feature extractor to learn
  per-point features from input point clouds, 2) the superpoint constructor to progressively
  grow the sizes of superpoints, and 3) the semantic primitive clustering module to
  group superpoints into semantic elements for the final semantic segmentation. We
  extensively evaluate our method on multiple datasets, demonstrating superior performance
  over all unsupervised baselines and approaching the classic fullysupervised PointNet.
  We hope our work could inspire more advanced methods for unsupervised 3D semantic
  learning.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10203698/
---

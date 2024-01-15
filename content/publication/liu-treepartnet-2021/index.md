---
title: 'TreePartNet: neural decomposition of point clouds for 3D tree reconstruction'
authors:
- Yanchao Liu
- Jianwei Guo
- Bedrich Benes
- Oliver Deussen
- Xiaopeng Zhang
- Hui Huang
date: '2021-12-01'
publishDate: '2024-01-15T06:08:03.928360Z'
publication_types:
- article-journal
publication: '*ACM Transactions on Graphics*'
doi: 10.1145/3478513.3480486
abstract: We present TreePartNet , a neural network aimed at reconstructing tree geometry
  from point clouds obtained by scanning real trees. Our key idea is to learn a natural
  neural decomposition exploiting the assumption that a tree comprises locally cylindrical
  shapes. In particular, reconstruction is a two-step process. First, two networks
  are used to detect priors from the point clouds. One detects semantic branching
  points, and the other network is trained to learn a cylindrical representation of
  the branches. In the second step, we apply a neural merging module to reduce the
  cylindrical representation to a final set of generalized cylinders combined by branches.
  We demonstrate results of reconstructing realistic tree geometry for a variety of
  input models and with varying input point quality, e.g., noise, outliers, and incompleteness.
  We evaluate our approach extensively by using data from both synthetic and real
  trees and comparing it with alternative methods.
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3478513.3480486
---

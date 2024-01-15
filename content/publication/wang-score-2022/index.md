---
title: 'Score Jacobian Chaining: Lifting Pretrained 2D Diffusion Models for 3D Generation'
authors:
- Haochen Wang
- Xiaodan Du
- Jiahao Li
- Raymond A. Yeh
- Greg Shakhnarovich
date: '2022-12-01'
publishDate: '2024-01-15T06:08:03.935641Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: A diffusion model learns to predict a vector ﬁeld of gradients. We propose
  to apply chain rule on the learned gradients, and back-propagate the score of a
  diffusion model through the Jacobian of a differentiable renderer, which we instantiate
  to be a voxel radiance ﬁeld. This setup aggregates 2D scores at multiple camera
  viewpoints into a 3D score, and repurposes a pretrained 2D model for 3D data generation.
  We identify a technical challenge of distribution mismatch that arises in this application,
  and propose a novel estimation mechanism to resolve it. We run our algorithm on
  several offthe-shelf diffusion image generative models, including the recently released
  Stable Diffusion trained on the large-scale LAION 5B dataset.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2212.00774
---

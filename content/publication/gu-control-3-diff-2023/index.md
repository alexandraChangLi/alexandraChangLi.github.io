---
title: 'Control3Diff: Learning Controllable 3D Diffusion Models from Single-view Images'
authors:
- Jiatao Gu
- Qingzhe Gao
- Shuangfei Zhai
- Baoquan Chen
- Lingjie Liu
- Josh Susskind
date: '2023-10-01'
publishDate: '2024-01-15T06:08:03.964973Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Diffusion models have recently become the de-facto approach for generative
  modeling in the 2D domain. However, extending diffusion models to 3D is challenging
  due to the difficulties in acquiring 3D ground truth data for training. On the other
  hand, 3D GANs that integrate implicit 3D representations into GANs have shown remarkable
  3D-aware generation when trained only on single-view image datasets. However, 3D
  GANs do not provide straightforward ways to precisely control image synthesis. To
  address these challenges, We present Control3Diff, a 3D diffusion model that combines
  the strengths of diffusion models and 3D GANs for versatile, controllable 3D-aware
  image synthesis for single-view datasets. Control3Diff explicitly models the underlying
  latent distribution (optionally conditioned on external inputs), thus enabling direct
  control during the diffusion process. Moreover, our approach is general and applicable
  to any type of controlling input, allowing us to train it with the same diffusion
  objective without any auxiliary supervision. We validate the efficacy of Control3Diff
  on standard image generation benchmarks, including FFHQ, AFHQ, and ShapeNet, using
  various conditioning inputs such as images, sketches, and text prompts. Please see
  the project website (urlhttps://jiataogu.me/control3diff) for video comparisons.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2304.06700
---

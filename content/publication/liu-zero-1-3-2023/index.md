---
title: 'Zero-1-to-3: Zero-shot One Image to 3D Object'
authors:
- Ruoshi Liu
- Rundi Wu
- Basile Van Hoorick
- Pavel Tokmakov
- Sergey Zakharov
- Carl Vondrick
date: '2023-03-01'
publishDate: '2024-01-15T06:08:03.728568Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: We introduce Zero-1-to-3, a framework for changing the camera viewpoint
  of an object given just a single RGB image. To perform novel view synthesis in this
  under-constrained setting, we capitalize on the geometric priors that large-scale
  diffusion models learn about natural images. Our conditional diffusion model uses
  a synthetic dataset to learn controls of the relative camera viewpoint, which allow
  new images to be generated of the same object under a specified camera transformation.
  Even though it is trained on a synthetic dataset, our model retains a strong zero-shot
  generalization ability to out-of-distribution datasets as well as in-the-wild images,
  including impressionist paintings. Our viewpoint-conditioned diffusion approach
  can further be used for the task of 3D reconstruction from a single image. Qualitative
  and quantitative experiments show that our method significantly outperforms state-of-the-art
  single-view 3D reconstruction and novel view synthesis models by leveraging Internet-scale
  pre-training.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Graphics
- Computer Science - Robotics
links:
- name: URL
  url: http://arxiv.org/abs/2303.11328
---

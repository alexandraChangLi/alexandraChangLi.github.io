---
title: 'ShapeCrafter: A Recursive Text-Conditioned 3D Shape Generation Model'
authors:
- Rao Fu
- Xiao Zhan
- Yiwen Chen
- Daniel Ritchie
- Srinath Sridhar
date: '2023-04-01'
publishDate: '2024-01-15T06:08:03.620277Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: We present ShapeCrafter, a neural network for recursive text-conditioned
  3D shape generation. Existing methods that generate text-conditioned 3D shapes consume
  an entire text prompt to generate a 3D shape in a single step. However, humans tend
  to describe shapes recursively—we may start with an initial description and progressively
  add details based on intermediate results. To capture this recursive process, we
  introduce a method to generate a 3D shape distribution, conditioned on an initial
  phrase, that gradually evolves as more phrases are added. Since existing datasets
  are insufﬁcient for training under this approach, we present Text2Shape++, a large
  dataset of 369K shape–text pairs that supports recursive shape generation. To capture
  local details that are often used to reﬁne shape descriptions, we build upon vector-quantized
  deep implicit functions that generate a distribution of high-quality shapes. Results
  show that our method can generate shapes consistent with text descriptions, and
  shapes evolve gradually as more phrases are added. Our method supports shape editing,
  extrapolation, and can enable new applications in human–machine collaboration for
  creative design.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Artificial Intelligence
links:
- name: URL
  url: http://arxiv.org/abs/2207.09446
---

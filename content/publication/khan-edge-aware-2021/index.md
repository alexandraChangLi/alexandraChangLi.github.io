---
title: Edge-aware Bidirectional Diffusion for Dense Depth Estimation from Light Fields
authors:
- Numair Khan
- Min H. Kim
- James Tompkin
date: '2021-07-01'
publishDate: '2024-01-15T06:08:03.658452Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: We present an algorithm to estimate fast and accurate depth maps from light
  fields via a sparse set of depth edges and gradients. Our proposed approach is based
  around the idea that true depth edges are more sensitive than texture edges to local
  constraints, and so they can be reliably disambiguated through a bidirectional diffusion
  process. First, we use epipolar-plane images to estimate sub-pixel disparity at
  a sparse set of pixels. To find sparse points efficiently, we propose an entropy-based
  refinement approach to a line estimate from a limited set of oriented filter banks.
  Next, to estimate the diffusion direction away from sparse points, we optimize constraints
  at these points via our bidirectional diffusion method. This resolves the ambiguity
  of which surface the edge belongs to and reliably separates depth from texture edges,
  allowing us to diffuse the sparse set in a depth-edge and occlusion-aware manner
  to obtain accurate dense depth maps.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2107.02967
---

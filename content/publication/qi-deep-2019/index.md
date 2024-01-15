---
title: Deep Hough Voting for 3D Object Detection in Point Clouds
authors:
- Charles R. Qi
- Or Litany
- Kaiming He
- Leonidas J. Guibas
date: '2019-08-01'
publishDate: '2024-01-15T06:08:04.291746Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'Current 3D object detection methods are heavily inﬂuenced by 2D detectors.
  In order to leverage architectures in 2D detectors, they often convert 3D point
  clouds to regular grids (i.e., to voxel grids or to bird’s eye view images), or
  rely on detection in 2D images to propose 3D boxes. Few works have attempted to
  directly detect objects in point clouds. In this work, we return to ﬁrst principles
  to construct a 3D detection pipeline for point cloud data and as generic as possible.
  However, due to the sparse nature of the data – samples from 2D manifolds in 3D
  space – we face a major challenge when directly predicting bounding box parameters
  from scene points: a 3D object centroid can be far from any surface point thus hard
  to regress accurately in one step. To address the challenge, we propose VoteNet,
  an end-to-end 3D object detection network based on a synergy of deep point set networks
  and Hough voting. Our model achieves state-of-the-art 3D detection on two large
  datasets of real 3D scans, ScanNet and SUN RGB-D with a simple design, compact model
  size and high efﬁciency. Remarkably, VoteNet outperforms previous methods by using
  purely geometric information without relying on color images.'
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/1904.09664
---

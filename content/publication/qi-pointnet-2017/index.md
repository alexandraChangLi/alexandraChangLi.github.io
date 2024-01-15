---
title: 'PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space'
authors:
- Charles R. Qi
- Li Yi
- Hao Su
- Leonidas J. Guibas
date: '2017-06-01'
publishDate: '2024-01-15T06:08:03.597737Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Few prior works study deep learning on point sets. PointNet [20] is a pioneer
  in this direction. However, by design PointNet does not capture local structures
  induced by the metric space points live in, limiting its ability to recognize ﬁne-grained
  patterns and generalizability to complex scenes. In this work, we introduce a hierarchical
  neural network that applies PointNet recursively on a nested partitioning of the
  input point set. By exploiting metric space distances, our network is able to learn
  local features with increasing contextual scales. With further observation that
  point sets are usually sampled with varying densities, which results in greatly
  decreased performance for networks trained on uniform densities, we propose novel
  set learning layers to adaptively combine features from multiple scales. Experiments
  show that our network called PointNet++ is able to learn deep point set features
  efﬁciently and robustly. In particular, results signiﬁcantly better than state-of-the-art
  have been obtained on challenging benchmarks of 3D point clouds.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/1706.02413
---

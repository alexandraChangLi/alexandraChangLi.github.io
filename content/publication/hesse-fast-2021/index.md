---
title: Fast Axiomatic Attribution for Neural Networks
authors:
- Robin Hesse
- Simone Schaub-Meyer
- Stefan Roth
date: '2021-11-01'
publishDate: '2024-01-15T06:08:03.469374Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Mitigating the dependence on spurious correlations present in the training
  dataset is a quickly emerging and important topic of deep learning. Recent approaches
  include priors on the feature attribution of a deep neural network (DNN) into the
  training process to reduce the dependence on unwanted features. However, until now
  one needed to trade off high-quality attributions, satisfying desirable axioms,
  against the time required to compute them. This in turn either led to long training
  times or ineffective attribution priors. In this work, we break this trade-off by
  considering a special class of efﬁciently axiomatically attributable DNNs for which
  an axiomatic feature attribution can be computed with only a single forward/backward
  pass. We formally prove that nonnegatively homogeneous DNNs, here termed X -DNNs,
  are efﬁciently axiomatically attributable and show that they can be effortlessly
  constructed from a wide range of regular DNNs by simply removing the bias term of
  each layer. Various experiments demonstrate the advantages of X -DNNs, beating state-of-the-art
  generic attribution methods on regular DNNs for training with attribution priors.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2111.07668
---

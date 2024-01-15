---
title: Learning to Estimate Shapley Values with Vision Transformers
authors:
- Ian Covert
- Chanwoo Kim
- Su-In Lee
date: '2023-03-01'
publishDate: '2024-01-15T06:08:04.195911Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Transformers have become a default architecture in computer vision, but
  understanding what drives their predictions remains a challenging problem. Current
  explanation approaches rely on attention values or input gradients, but these provide
  a limited view of a model’s dependencies. Shapley values offer a theoretically sound
  alternative, but their computational cost makes them impractical for large, high-dimensional
  models. In this work, we aim to make Shapley values practical for vision transformers
  (ViTs). To do so, we ﬁrst leverage an attention masking approach to evaluate ViTs
  with partial information, and we then develop a procedure to generate Shapley value
  explanations via a separate, learned explainer model. Our experiments compare Shapley
  values to many baseline methods (e.g., attention rollout, GradCAM, LRP), and we
  ﬁnd that our approach provides more accurate explanations than existing methods
  for ViTs.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2206.05282
---

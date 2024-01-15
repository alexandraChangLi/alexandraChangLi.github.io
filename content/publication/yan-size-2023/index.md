---
title: 'Size Generalization of Graph Neural Networks on Biological Data: Insights
  and Practices from the Spectral Perspective'
authors:
- Yujun Yan
- Gaotang Li
- Danai koutra
date: '2023-09-01'
publishDate: '2024-01-15T06:08:03.860873Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'We investigate size-induced distribution shifts in graphs and assess their
  impact on the ability of graph neural networks (GNNs) to generalize to larger graphs
  relative to the training data. Existing literature presents conflicting conclusions
  on GNNs’ size generalizability, primarily due to disparities in application domains
  and underlying assumptions concerning size-induced distribution shifts. Motivated
  by this, we take a data-driven approach: we focus on real biological datasets and
  seek to characterize the types of size-induced distribution shifts. Diverging from
  prior approaches, we adopt a spectral perspective and identify that spectrum differences
  induced by size are related to differences in subgraph patterns (e.g., average cycle
  lengths). We further find that common GNNs cannot capture these subgraph patterns,
  resulting in performance decline when testing on larger graphs. Based on these spectral
  insights, we introduce and compare three model-agnostic strategies aimed at making
  GNNs aware of important subgraph patterns to enhance their size generalizability:
  self-supervision, augmentation, and size-insensitive attention. Our empirical results
  reveal that all strategies enhance GNNs’ size generalizability, with simple size-insensitive
  attention surprisingly emerging as the most effective method. Notably, this strategy
  substantially enhances graph classification performance on large test graphs, which
  are 2-10 times larger than the training graphs, resulting in an improvement in F1
  scores by up to 8%.'
tags:
- Computer Science - Machine Learning
- Computer Science - Artificial Intelligence
links:
- name: URL
  url: http://arxiv.org/abs/2305.15611
---

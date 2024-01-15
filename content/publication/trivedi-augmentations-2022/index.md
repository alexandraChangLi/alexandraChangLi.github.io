---
title: 'Augmentations in Graph Contrastive Learning: Current Methodological Flaws
  & Towards Better Practices'
authors:
- Puja Trivedi
- Ekdeep Singh Lubana
- Yujun Yan
- Yaoqing Yang
- Danai Koutra
date: '2022-03-01'
publishDate: '2024-01-15T06:08:03.759561Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Unsupervised graph representation learning is critical to a wide range of
  applications where labels may be scarce or expensive to procure. Contrastive learning
  (CL) is an increasingly popular paradigm for such settings and the state-of-the-art
  in unsupervised visual representation learning. Recent work attributes the success
  of visual CL to use of task-relevant augmentations and large, diverse datasets.
  Interestingly, graph CL frameworks report strong performance despite using orders
  of magnitude smaller datasets and employing domain-agnostic graph augmentations
  (DAGAs). Motivated by this discrepancy, we probe the quality of representations
  learnt by popular graph CL frameworks using DAGAs. We find that DAGAs can destroy
  task-relevant information and harm the model’s ability to learn discriminative representations.
  On small benchmark datasets, we show the inductive bias of graph neural networks
  can significantly compensate for this weak discriminability. Based on our findings,
  we propose several sanity checks that enable practitioners to quickly assess the
  quality of their model’s learned representations. We further propose a broad strategy
  for designing task-aware augmentations that are amenable to graph CL and demonstrate
  its efficacy on two large-scale, complex graph applications. For example, in graph-based
  document classification, we show task-relevant augmentations improve accuracy up
  to 20%.
tags:
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2111.03220
---

---
title: 'Interpretable Sparsification of Brain Graphs: Better Practices and Effective
  Designs for Graph Neural Networks'
authors:
- Gaotang Li
- Marlena Duda
- Xiang Zhang
- Danai Koutra
- Yujun Yan
date: '2023-08-01'
publishDate: '2024-01-15T06:08:03.868667Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery
  and Data Mining*'
doi: 10.1145/3580305.3599394
abstract: 'Brain graphs, which model the structural and functional relationships between
  brain regions, are crucial in neuroscientific and clinical applications involving
  graph classification. However, dense brain graphs pose computational challenges
  including high runtime and memory usage and limited interpretability. In this paper,
  we investigate effective designs in Graph Neural Networks (GNNs) to sparsify brain
  graphs by eliminating noisy edges. While prior works remove noisy edges based on
  explainability or task-irrelevant properties, their effectiveness in enhancing performance
  with sparsified graphs is not guaranteed. Moreover, existing approaches often overlook
  collective edge removal across multiple graphs. To address these issues, we introduce
  an iterative framework to analyze different sparsification models. Our findings
  are as follows: (i) methods prioritizing interpretability may not be suitable for
  graph sparsification as they can degrade GNNs’ performance in graph classification
  tasks; (ii) simultaneously learning edge selection with GNN training is more beneficial
  than post-training; (iii) a shared edge selection across graphs outperforms separate
  selection for each graph; and (iv) task-relevant gradient information aids in edge
  selection. Based on these insights, we propose a new model, Interpretable Graph
  Sparsification (IGS), which enhances graph classification performance by up to 5.1%
  with 55.0% fewer edges. The retained edges identified by IGS provide neuroscientific
  interpretations and are supported by well-established literature.'
tags:
- Computer Science - Machine Learning
- Quantitative Biology - Neurons and Cognition
links:
- name: URL
  url: http://arxiv.org/abs/2306.14375
---

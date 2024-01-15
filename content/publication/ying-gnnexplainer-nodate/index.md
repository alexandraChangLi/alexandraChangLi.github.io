---
title: 'GNNExplainer: Generating Explanations for Graph Neural Networks'
authors:
- Zhitao Ying
- Dylan Bourgeois
- Jiaxuan You
- Marinka Zitnik
- Jure Leskovec
date: -01-01
publishDate: '2024-01-15T06:08:03.476799Z'
publication_types:
- article-journal
abstract: Graph Neural Networks (GNNs) are a powerful tool for machine learning on
  graphs. GNNs combine node feature information with the graph structure by recursively
  passing neural messages along edges of the input graph. However, incorporating both
  graph structure and feature information leads to complex models and explaining predictions
  made by GNNs remains unsolved. Here we propose GNNEXPLAINER, the ﬁrst general, model-agnostic
  approach for providing interpretable explanations for predictions of any GNN-based
  model on any graph-based machine learning task. Given an instance, GNNEXPLAINER
  identiﬁes a compact subgraph structure and a small subset of node features that
  have a crucial role in GNN’s prediction. Further, GNNEXPLAINER can generate consistent
  and concise explanations for an entire class of instances. We formulate GNNEXPLAINER
  as an optimization task that maximizes the mutual information between a GNN’s prediction
  and distribution of possible subgraph structures. Experiments on synthetic and real-world
  graphs show that our approach can identify important graph structures as well as
  node features, and outperforms alternative baseline approaches by up to 43.0% in
  explanation accuracy. GNNEXPLAINER provides a variety of beneﬁts, from the ability
  to visualize semantically relevant structures to interpretability, to giving insights
  into errors of faulty GNNs.
---

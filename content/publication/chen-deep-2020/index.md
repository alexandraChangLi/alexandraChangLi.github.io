---
title: Deep Unsupervised Learning of 3D Point Clouds via Graph Topology Inference
  and Filtering
authors:
- Siheng Chen
- Chaojing Duan
- Yaoqing Yang
- Duanshun Li
- Chen Feng
- Dong Tian
date: '2020-01-01'
publishDate: '2024-01-15T06:08:03.750889Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Image Processing*'
doi: 10.1109/TIP.2019.2957935
abstract: 'We propose a deep autoencoder with graph topology inference and ﬁltering
  to achieve compact representations of unorganized 3D point clouds in an unsupervised
  manner. Many previous works discretize 3D points to voxels and then use latticebased
  methods to process and learn 3D spatial information; however, this leads to inevitable
  discretization errors. In this work, we try to handle raw 3D points without such
  compromise. The proposed networks follow the autoencoder framework with a focus
  on designing the decoder. The encoder of the proposed networks adopts similar architectures
  as in PointNet, which is a well-acknowledged method for supervised learning of 3D
  point clouds. The decoder of the proposed networks involves three novel modules:
  the folding module, the graph-topologyinference module, and the graph-ﬁltering module.
  The folding module folds a canonical 2D lattice to the underlying surface of a 3D
  point cloud, achieving coarse reconstruction; the graphtopology-inference module
  learns a graph topology to represent pairwise relationships between 3D points, pushing
  the latent code to preserve both coordinates and pairwise relationships of points
  in 3D point clouds; and the graph-ﬁltering module couples the above two modules,
  reﬁning the coarse reconstruction through a learnt graph topology to obtain the
  ﬁnal reconstruction. The proposed decoder leverages a learnable graph topology to
  push the codeword to preserve representative features and further improve the unsupervised-learning
  performance. We further provide theoretical analyses of the proposed architecture.
  We provide an upper bound for the reconstruction loss and further show the superiority
  of graph smoothness over spatial smoothness as a prior to model 3D point clouds.
  In the experiments, we validate the proposed networks in three tasks, including
  3D point cloud reconstruction, visualization, and transfer classiﬁcation. The experimental
  results show that (1) the proposed networks outperform the state-of-the-art methods
  in various tasks, including reconstruction and transfer classiﬁcation; (2) a graph
  topology can be inferred as auxiliary information without speciﬁc supervision on
  graph topology inference; (3) graph ﬁltering reﬁnes the reconstruction, leading
  to better performances; and (4) designing a powerful decoder could improve the unsupervisedlearning
  performance, just like a powerful encoder.'
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/1905.04571
---

---
title: 'PointCLIP: Point Cloud Understanding by CLIP'
authors:
- Renrui Zhang
- Ziyu Guo
- Wei Zhang
- Kunchang Li
- Xupeng Miao
- Bin Cui
- Yu Qiao
- Peng Gao
- Hongsheng Li
date: '2021-12-01'
publishDate: '2024-01-15T06:08:03.589702Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'Recently, zero-shot and few-shot learning via Contrastive Vision-Language
  Pre-training (CLIP) have shown inspirational performance on 2D visual recognition,
  which learns to match images with their corresponding texts in open-vocabulary settings.
  However, it remains under explored that whether CLIP, pre-trained by large-scale
  imagetext pairs in 2D, can be generalized to 3D recognition. In this paper, we identify
  such a setting is feasible by proposing PointCLIP, which conducts alignment between
  CLIPencoded point cloud and 3D category texts. Speciﬁcally, we encode a point cloud
  by projecting it into multi-view depth maps without rendering, and aggregate the
  view-wise zeroshot prediction to achieve knowledge transfer from 2D to 3D. On top
  of that, we design an inter-view adapter to better extract the global feature and
  adaptively fuse the few-shot knowledge learned from 3D into CLIP pre-trained in
  2D. By just ﬁne-tuning the lightweight adapter in the few-shot settings, the performance
  of PointCLIP could be largely improved. In addition, we observe the complementary
  property between PointCLIP and classical 3D-supervised networks. By simple ensembling,
  PointCLIP boosts baseline’s performance and even surpasses state-of-the-art models.
  Therefore, PointCLIP is a promising alternative for effective 3D point cloud understanding
  via CLIP under low resource cost and data regime. We conduct thorough experiments
  on widely-adopted ModelNet10, ModelNet40 and the challenging ScanObjectNN to demonstrate
  the effectiveness of PointCLIP. The code is released at https: //github.com/ZrrSkywalker/PointCLIP.'
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Artificial Intelligence
- Computer Science - Robotics
links:
- name: URL
  url: http://arxiv.org/abs/2112.02413
---

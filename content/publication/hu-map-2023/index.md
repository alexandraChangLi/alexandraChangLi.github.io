---
title: 'MAP: Domain Generalization via Meta-Learning on Anatomy-Consistent Pseudo-Modalities'
authors:
- Dewei Hu
- Hao Li
- Han Liu
- Xing Yao
- Jiacheng Wang
- Ipek Oguz
date: '2023-09-01'
publishDate: '2024-01-15T06:08:04.061479Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Deep models suffer from limited generalization capability to unseen domains,
  which has severely hindered their clinical applicability. Specifically for the retinal
  vessel segmentation task, although the model is supposed to learn the anatomy of
  the target, it can be distracted by confounding factors like intensity and contrast.
  We propose Meta learning on Anatomy-consistent Pseudo-modalities (MAP), a method
  that improves model generalizability by learning structural features. We first leverage
  a feature extraction network to generate three distinct pseudo-modalities that share
  the vessel structure of the original image. Next, we use the episodic learning paradigm
  by selecting one of the pseudo-modalities as the meta-train dataset, and perform
  meta-testing on a continuous augmented image space generated through Dirichlet mixup
  of the remaining pseudo-modalities. Further, we introduce two loss functions that
  facilitate the model’s focus on shape information by clustering the latent vectors
  obtained from images featuring identical vasculature. We evaluate our model on seven
  public datasets of various retinal imaging modalities and we conclude that MAP has
  substantially better generalizability. Our code is publically available at https://github.com/DeweiHu/MAP.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2309.01286
---

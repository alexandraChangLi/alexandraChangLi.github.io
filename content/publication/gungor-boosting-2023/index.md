---
title: Boosting Weakly Supervised Object Detection using Fusion and Priors from Hallucinated
  Depth
authors:
- Cagri Gungor
- Adriana Kovashka
date: '2023-11-01'
publishDate: '2024-01-15T06:08:04.025546Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Despite recent attention to depth for various tasks, it is still an unexplored
  modality for weakly-supervised object detection (WSOD). We propose an amplifier
  method for enhancing the performance of WSOD by integrating depth information. Our
  approach can be applied to different WSOD methods based on multiple-instance learning,
  without necessitating additional annotations or inducing large computational cost.
  Our proposed method employs monocular depth estimation to obtain hallucinated depth
  information, which is then incorporated into a Siamese WSOD network using contrastive
  loss and fusion. By analyzing the relationship between language context and depth,
  we calculate depth priors to identify the bounding box proposals that may contain
  an object of interest. These depth priors are then utilized to update the list of
  pseudo ground-truth boxes, or adjust the confidence of per-box predictions. We evaluate
  our proposed method on three datasets (COCO, PASCAL VOC, and Conceptual Captions)
  by implementing it on top of two state-of-the-art WSOD methods, and we demonstrate
  a substantial enhancement in performance.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2303.10937
---

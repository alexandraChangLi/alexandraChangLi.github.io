---
title: End-to-End Object Detection with Transformers
authors:
- Nicolas Carion
- Francisco Massa
- Gabriel Synnaeve
- Nicolas Usunier
- Alexander Kirillov
- Sergey Zagoruyko
date: '2020-05-01'
publishDate: '2024-01-15T06:08:04.247109Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: We present a new method that views object detection as a direct set prediction
  problem. Our approach streamlines the detection pipeline, eﬀectively removing the
  need for many hand-designed components like a non-maximum suppression procedure
  or anchor generation that explicitly encode our prior knowledge about the task.
  The main ingredients of the new framework, called DEtection TRansformer or DETR,
  are a set-based global loss that forces unique predictions via bipartite matching,
  and a transformer encoder-decoder architecture. Given a ﬁxed small set of learned
  object queries, DETR reasons about the relations of the objects and the global image
  context to directly output the ﬁnal set of predictions in parallel. The new model
  is conceptually simple and does not require a specialized library, unlike many other
  modern detectors. DETR demonstrates accuracy and run-time performance on par with
  the well-established and highly-optimized Faster RCNN baseline on the challenging
  COCO object detection dataset. Moreover, DETR can be easily generalized to produce
  panoptic segmentation in a uniﬁed manner. We show that it signiﬁcantly outperforms
  competitive baselines. Training code and pretrained models are available at https://github.com/facebookresearch/detr.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2005.12872
---

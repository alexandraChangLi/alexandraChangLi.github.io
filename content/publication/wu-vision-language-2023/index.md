---
title: Vision-Language Dataset Distillation
authors:
- Xindi Wu
- Byron Zhang
- Zhiwei Deng
- Olga Russakovsky
date: '2023-10-01'
publishDate: '2024-01-15T06:08:03.898175Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'Dataset distillation methods promise to reduce large-scale datasets down
  to significantly smaller sets of (potentially synthetic) training examples, which
  preserve sufficient information for training a new model from scratch. So far, dataset
  distillation methods have been developed for image classification. However, with
  the rise in capabilities of vision-language models (VLMs), and especially given
  the scale of datasets necessary to train these models, the time is ripe to expand
  dataset distillation methods beyond image classification. In this work, we take
  the first steps towards this goal by expanding the idea of trajectory matching to
  create a distillation method for vision-language datasets. A key challenge is that
  vision-language datasets do not have a set of discrete classes. To overcome this,
  our proposed vision-language dataset distillation method jointly distills the image-text
  pairs in a contrastive formulation. Since there are no existing baselines, we compare
  our approach to three coreset selection methods (strategic subsampling of the training
  dataset), which we adapt to the vision-language setting. We demonstrate significant
  improvements on the challenging Flickr30K and COCO retrieval benchmarks: for example,
  on Flickr30K, the best coreset selection method selecting 1000 image-text pairs
  for training achieves only 5.6% image-to-text retrieval accuracy (i.e., recall@1);
  in contrast, our dataset distillation approach almost doubles that to 9.9% with
  just 100 (an order of magnitude fewer) training pairs.'
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2308.07545
---

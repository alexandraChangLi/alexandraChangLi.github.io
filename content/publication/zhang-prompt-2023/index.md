---
title: 'Prompt, Generate, then Cache: Cascade of Foundation Models makes Strong Few-shot
  Learners'
authors:
- Renrui Zhang
- Xiangfei Hu
- Bohao Li
- Siyuan Huang
- Hanqiu Deng
- Hongsheng Li
- Yu Qiao
- Peng Gao
date: '2023-03-01'
publishDate: '2024-01-15T06:08:03.575180Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Visual recognition in low-data regimes requires deep neural networks to
  learn generalized representations from limited training samples. Recently, CLIP-based
  methods have shown promising few-shot performance beneﬁted from the contrastive
  language-image pre-training. We then question, if the more diverse pre-training
  knowledge can be cascaded to further assist few-shot representation learning. In
  this paper, we propose CaFo, a Cascade of Foundation models that incorporates diverse
  prior knowledge of various pretraining paradigms for better few-shot learning. Our
  CaFo incorporates CLIP’s language-contrastive knowledge, DINO’s vision-contrastive
  knowledge, DALL-E’s visiongenerative knowledge, and GPT-3’s language-generative
  knowledge. Speciﬁcally, CaFo works by ‘Prompt, Generate, then Cache’. Firstly, we
  leverage GPT-3 to produce textual inputs for prompting CLIP with rich downstream
  linguistic semantics. Then, we generate synthetic images via DALL-E to expand the
  few-shot training data without any manpower. At last, we introduce a learnable cache
  model to adaptively blend the predictions from CLIP and DINO. By such collaboration,
  CaFo can fully unleash the potential of different pre-training methods and unify
  them to perform state-ofthe-art for few-shot classiﬁcation. Code is available at
  https://github.com/ZrrSkywalker/CaFo.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Computation and Language
links:
- name: URL
  url: http://arxiv.org/abs/2303.02151
---

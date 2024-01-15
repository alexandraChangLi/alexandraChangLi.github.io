---
title: 'ImageNet-OOD: Deciphering Modern Out-of-Distribution Detection Algorithms'
authors:
- William Yang
- Byron Zhang
- Olga Russakovsky
date: '2023-10-01'
publishDate: '2024-01-15T06:08:03.905812Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'The task of out-of-distribution (OOD) detection is notoriously ill-defined.
  Earlier works focused on new-class detection, aiming to identify label-altering
  data distribution shifts, also known as \"semantic shift.\" However, recent works
  argue for a focus on failure detection, expanding the OOD evaluation framework to
  account for label-preserving data distribution shifts, also known as \"covariate
  shift.\" Intriguingly, under this new framework, complex OOD detectors that were
  previously considered state-of-the-art now perform similarly to, or even worse than
  the simple maximum softmax probability baseline. This raises the question: what
  are the latest OOD detectors actually detecting? Deciphering the behavior of OOD
  detection algorithms requires evaluation datasets that decouples semantic shift
  and covariate shift. To aid our investigations, we present ImageNet-OOD, a clean
  semantic shift dataset that minimizes the interference of covariate shift. Through
  comprehensive experiments, we show that OOD detectors are more sensitive to covariate
  shift than to semantic shift, and the benefits of recent OOD detection algorithms
  on semantic shift detection is minimal. Our dataset and analyses provide important
  insights for guiding the design of future OOD detectors.'
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2310.01755
---

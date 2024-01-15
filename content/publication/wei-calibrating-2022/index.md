---
title: Calibrating Histopathology Image Classifiers using Label Smoothing
authors:
- Jerry Wei
- Lorenzo Torresani
- Jason Wei
- Saeed Hassanpour
date: '2022-01-01'
publishDate: '2024-01-15T06:08:03.837999Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: 'The classiﬁcation of histopathology images fundamentally differs from traditional
  image classiﬁcation tasks because histopathology images naturally exhibit a range
  of diagnostic features, resulting in a diverse range of annotator agreement levels.
  However, examples with high annotator disagreement are often either assigned the
  majority label or discarded entirely when training histopathology image classiﬁers.
  This widespread practice often yields classiﬁers that do not account for example
  difﬁculty and exhibit poor model calibration. In this paper, we ask: can we improve
  model calibration by endowing histopathology image classiﬁers with inductive biases
  about example difﬁculty? We propose several label smoothing methods that utilize
  per-image annotator agreement. Though our methods are simple, we ﬁnd that they substantially
  improve model calibration, while maintaining (or even improving) accuracy. For colorectal
  polyp classiﬁcation, a common yet challenging task in gastrointestinal pathology,
  we ﬁnd that our proposed agreement-aware label smoothing methods reduce calibration
  error by almost 70%. Moreover, we ﬁnd that using model conﬁdence as a proxy for
  annotator agreement also improves calibration and accuracy, suggesting that datasets
  without multiple annotators can still beneﬁt from our proposed label smoothing methods
  via our proposed conﬁdence-aware label smoothing methods.'
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Electrical Engineering and Systems Science - Image and Video Processing
links:
- name: URL
  url: http://arxiv.org/abs/2201.11866
---

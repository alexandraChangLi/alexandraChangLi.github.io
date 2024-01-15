---
title: Tree Instance Segmentation with Temporal Contour Graph
authors:
- Adnan Firoze
- Cameron Wingren
- Raymond A. Yeh
- Bedrich Benes
- Daniel Aliaga
date: '2023-06-01'
publishDate: '2024-01-15T06:08:03.942826Z'
publication_types:
- paper-conference
publication: '*2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition
  (CVPR)*'
doi: 10.1109/CVPR52729.2023.00218
abstract: We present a novel approach to perform instance segmentation and counting
  for densely packed self-similar trees using a top-view RGB image sequence. We propose
  a solution that leverages pixel content, shape, and selfocclusion. First, we perform
  an initial over-segmentation of the image sequence and aggregate structural characteristics
  into a contour graph with temporal information incorporated. Second, using a graph
  convolutional network and its inherent local messaging passing abilities, we merge
  adjacent tree crown patches into a final set of tree crowns. Per various studies
  and comparisons, our method is superior to all prior methods and results in high-accuracy
  instance segmentation and counting despite the trees being tightly packed. Finally,
  we provide various forest image sequence datasets suitable for subsequent benchmarking
  and evaluation captured at different altitudes and leaf conditions.
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/10204310/
---

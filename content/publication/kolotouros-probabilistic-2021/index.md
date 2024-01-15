---
title: Probabilistic Modeling for Human Mesh Recovery
authors:
- Nikos Kolotouros
- Georgios Pavlakos
- Dinesh Jayaraman
- Kostas Daniilidis
date: '2021-10-01'
publishDate: '2024-01-15T06:08:03.957304Z'
publication_types:
- paper-conference
publication: '*2021 IEEE/CVF International Conference on Computer Vision (ICCV)*'
doi: 10.1109/ICCV48922.2021.01140
abstract: 'This paper focuses on the problem of 3D human reconstruction from 2D evidence.
  Although this is an inherently ambiguous problem, the majority of recent works avoid
  the uncertainty modeling and typically regress a single estimate for a given input.
  In contrast to that, in this work, we propose to embrace the reconstruction ambiguity
  and we recast the problem as learning a mapping from the input to a distribution
  of plausible 3D poses. Our approach is based on the normalizing ﬂows model and offers
  a series of advantages. For conventional applications, where a single 3D estimate
  is required, our formulation allows for efﬁcient mode computation. Using the mode
  leads to performance that is comparable with the state of the art among deterministic
  unimodal regression models. Simultaneously, since we have access to the likelihood
  of each sample, we demonstrate that our model is useful in a series of downstream
  tasks, where we leverage the probabilistic nature of the prediction as a tool for
  more accurate estimation. These tasks include reconstruction from multiple uncalibrated
  views, as well as human model ﬁtting, where our model acts as a powerful image-based
  prior for mesh recovery. Our results validate the importance of probabilistic modeling,
  and indicate state-of-the-art performance across a variety of settings. Code and
  models are available at: https://www.seas.upenn.edu/ ˜nkolot/projects/prohmr.'
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/9710873/
---

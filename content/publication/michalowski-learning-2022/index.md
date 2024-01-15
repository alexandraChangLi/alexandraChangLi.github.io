---
title: Learning to Adapt Dynamic Clinical Event Sequences with Residual Mixture of
  Experts
authors:
- Jeong Min Lee
- Milos Hauskrecht
date: '2022-01-01'
publishDate: '2024-01-15T06:08:04.010881Z'
publication_types:
- chapter
publication: '*Artificial Intelligence in Medicine*'
doi: 10.1007/978-3-031-09342-5_15
abstract: Clinical event sequences in Electronic Health Records (EHRs) record detailed
  information about the patient condition and patient care as they occur in time.
  Recent years have witnessed increased interest of machine learning community in
  developing machine learning models solving diﬀerent types of problems deﬁned upon
  information in EHRs. More recently, neural sequential models, such as RNN and LSTM,
  became popular and widely applied models for representing patient sequence data
  and for predicting future events or outcomes based on such data. However, a single
  neural sequential model may not properly represent complex dynamics of all patients
  and the diﬀerences in their behaviors. In this work, we aim to alleviate this limitation
  by reﬁning a one-ﬁts-all model using a Mixture-of-Experts (MoE) architecture. The
  architecture consists of multiple (expert) RNN models covering patient sub-populations
  and reﬁning the predictions of the base model. That is, instead of training expert
  RNN models from scratch we deﬁne them on the residual signal that attempts to model
  the diﬀerences from the population-wide model. The heterogeneity of various patient
  sequences is modeled through multiple experts that consist of RNN. Particularly,
  instead of directly training MoE from scratch, we augment MoE based on the prediction
  signal from pretrained base GRU model. With this way, the mixture of experts can
  provide ﬂexible adaptation to the (limited) predictive power of the single base
  RNN model. We experiment with the newly proposed model on realworld EHRs data and
  the multivariate clinical event prediction task. We implement RNN using Gated Recurrent
  Units (GRU). We show 4.1% gain on AUPRC statistics compared to a single RNN prediction.
links:
- name: URL
  url: https://link.springer.com/10.1007/978-3-031-09342-5_15
---

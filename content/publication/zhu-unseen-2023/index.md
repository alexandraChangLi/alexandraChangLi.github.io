---
title: Unseen Image Synthesis with Diffusion Models
authors:
- Ye Zhu
- Yu Wu
- Zhiwei Deng
- Olga Russakovsky
- Yan Yan
date: '2023-10-01'
publishDate: '2024-01-15T06:08:03.913575Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: While the current trend in the generative field is scaling up towards larger
  models and more training data for generalized domain representations, we go the
  opposite direction in this work by synthesizing unseen domain images without additional
  training. We do so via latent sampling and geometric optimization using pre-trained
  and frozen Denoising Diffusion Probabilistic Models (DDPMs) on single-domain datasets.
  Our key observation is that DDPMs pre-trained even just on single-domain images
  are already equipped with sufficient representation abilities to reconstruct arbitrary
  images from the inverted latent encoding following bi-directional deterministic
  diffusion and denoising trajectories. This motivates us to investigate the statistical
  and geometric behaviors of the Out-Of-Distribution (OOD) samples from unseen image
  domains in the latent spaces along the denoising chain. Notably, we theoretically
  and empirically show that the inverted OOD samples also establish Gaussians that
  are distinguishable from the original In-Domain (ID) samples in the intermediate
  latent spaces, which allows us to sample from them directly. Geometrical domain-specific
  and model-dependent information of the unseen subspace (e.g., sample-wise distance
  and angles) is used to further optimize the sampled OOD latent encodings from the
  estimated Gaussian prior. We conduct extensive analysis and experiments using pre-trained
  diffusion models (DDPM, iDDPM) on different datasets (AFHQ, CelebA-HQ, LSUN-Church,
  and LSUN-Bedroom), proving the effectiveness of this novel perspective to explore
  and re-think the diffusion models' data synthesis generalization ability.
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Machine Learning
links:
- name: URL
  url: http://arxiv.org/abs/2310.09213
---

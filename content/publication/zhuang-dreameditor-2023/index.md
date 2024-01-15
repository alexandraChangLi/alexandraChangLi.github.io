---
title: 'DreamEditor: Text-Driven 3D Scene Editing with Neural Fields'
authors:
- Jingyu Zhuang
- Chen Wang
- Lingjie Liu
- Liang Lin
- Guanbin Li
date: '2023-09-01'
publishDate: '2024-01-15T06:08:03.972748Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Neural fields have achieved impressive advancements in view synthesis and
  scene reconstruction. However, editing these neural fields remains challenging due
  to the implicit encoding of geometry and texture information. In this paper, we
  propose DreamEditor, a novel framework that enables users to perform controlled
  editing of neural fields using text prompts. By representing scenes as mesh-based
  neural fields, DreamEditor allows localized editing within specific regions. DreamEditor
  utilizes the text encoder of a pretrained text-to-Image diffusion model to automatically
  identify the regions to be edited based on the semantics of the text prompts. Subsequently,
  DreamEditor optimizes the editing region and aligns its geometry and texture with
  the text prompts through score distillation sampling [29]. Extensive experiments
  have demonstrated that DreamEditor can accurately edit neural fields of real-world
  scenes according to the given text prompts while ensuring consistency in irrelevant
  areas. DreamEditor generates highly realistic textures and geometry, significantly
  surpassing previous works in both quantitative and qualitative evaluations.
tags:
- Computer Science - Computer Vision and Pattern Recognition
links:
- name: URL
  url: http://arxiv.org/abs/2306.13455
---

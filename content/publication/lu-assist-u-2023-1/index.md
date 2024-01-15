---
title: 'ASSIST-U: A System for Segmentation and Image Style Transfer for Ureteroscopy'
authors:
- Daiwei Lu
- Yifan Wu
- Ayberk Acar
- Xing Yao
- Jie Ying Wu
- Nicholas Kavoussi
- Ipek Oguz
date: '2023-11-01'
publishDate: '2024-01-15T06:08:04.136511Z'
publication_types:
- report
doi: 10.22541/au.169960983.39481168/v1
abstract: Kidney stones require surgical removal when they grow too large to be broken
  up externally or to pass on their own. Upper tract urothelial carcinoma are also
  sometimes treated endoscopically in a similar procedure. These surgeries are diﬃcult,
  particularly for trainees who often miss tumors, stones or stone fragments, requiring
  re-operation. One cause of diﬃculty is the high cognitive strain surgeons experience
  in creating accurate mental models during the endoscopic operation. Furthermore,
  there are no patient-speciﬁc simulators to facilitate training or standardized visualization
  tools for ureteroscopy despite its high prevalence. We propose ASSIST-U, a system
  to automatically create realistic ureteroscopy images and videos solely using preoperative
  CT images to address these unmet needs. We train a 3D UNet model to automatically
  segment CT images and construct 3D surfaces. These surfaces are then skeletonized
  for rendering and camera position tracking. Finally, we train a style transfer model
  using Contrastive Unpaired Translation (CUT) to synthesize realistic ureteroscopy
  images. Cross validation on the UNet model achieved a Dice score of 0.853 $pm$ 0.084
  for the CT segmentation step. CUT style transfer produced visually plausible images;
  the Kernel Inception Distance to real ureteroscopy images was reduced from 0.198
  (rendered) to 0.089 (synthesized). We also qualitatively demonstrate the entire
  pipeline from CT to synthesized ureteroscopy. The proposed ASSIST-U system shows
  promise for aiding surgeons in visualization of kidney ureteroscopy.
links:
- name: URL
  url: 
    https://www.authorea.com/users/698001/articles/686034-assist-u-a-system-for-segmentation-and-image-style-transfer-for-ureteroscopy?commit=7c9771cf15bde0b4ce04f62604b97a6feb07b0e2
---

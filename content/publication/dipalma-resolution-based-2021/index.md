---
title: Resolution-based distillation for efficient histology image classification
authors:
- Joseph DiPalma
- Arief A. Suriawinata
- Laura J. Tafe
- Lorenzo Torresani
- Saeed Hassanpour
date: '2021-09-01'
publishDate: '2024-01-15T06:08:03.783171Z'
publication_types:
- article-journal
publication: '*Artificial Intelligence in Medicine*'
doi: 10.1016/j.artmed.2021.102136
abstract: Developing deep learning models to analyze histology images has been computationally
  challenging, as the massive size of the images causes excessive strain on all parts
  of the computing pipeline. This paper proposes a novel deep learning-based methodology
  for improving the computational efficiency of histology image classi­ fication.
  The proposed approach is robust when used with images that have reduced input resolution,
  and it can be trained effectively with limited labeled data. Moreover, our approach
  operates at either the tissue- or slidelevel, removing the need for laborious patch-level
  labeling. Our method uses knowledge distillation to trans­ fer knowledge from a
  teacher model pre-trained at high resolution to a student model trained on the same
  images at a considerably lower resolution. Also, to address the lack of large-scale
  labeled histology image datasets, we perform the knowledge distillation in a self-supervised
  fashion. We evaluate our approach on three distinct histology image datasets associated
  with celiac disease, lung adenocarcinoma, and renal cell carcinoma. Our results
  on these datasets demonstrate that a combination of knowledge distillation and self-supervision
  allows the student model to approach and, in some cases, surpass the teacher model's
  classification accuracy while being much more computationally efficient. Additionally,
  we observe an increase in student classification performance as the size of the
  unlabeled dataset increases, indicating that there is potential for this method
  to scale further with additional unlabeled data. Our model outperforms the high-resolution
  teacher model for celiac disease in accuracy, F1-score, precision, and recall while
  requiring 4 times fewer computations. For lung adenocarcinoma, our results at 1.25×
  magnification are within 1.5% of the results for the teacher model at 10× magnification,
  with a reduction in computational cost by a factor of 64. Our model on renal cell
  carcinoma at 1.25× magni­ fication performs within 1% of the teacher model at 5×
  magnification while requiring 16 times fewer compu­ tations. Furthermore, our celiac
  disease outcomes benefit from additional performance scaling with the use of more
  unlabeled data. In the case of 0.625× magnification, using unlabeled data improves
  accuracy by 4% over the tissue-level baseline. Therefore, our approach can improve
  the feasibility of deep learning solutions for digital pathology on standard computational
  hardware and infrastructures.
links:
- name: URL
  url: https://linkinghub.elsevier.com/retrieve/pii/S0933365721001299
---

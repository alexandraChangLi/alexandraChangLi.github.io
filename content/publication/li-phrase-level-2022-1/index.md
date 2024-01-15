---
title: Phrase-level Prediction for Video Temporal Localization
authors:
- Sizhe Li
date: '2022-01-01'
publishDate: '2024-01-15T06:10:56.385479Z'
publication_types:
- article-journal
abstract: Video temporal localization aims to locate a period that semantically matches
  a natural language query in a given untrimmed video. We empirically observe that
  although existing approaches gain steady progress on sentence localization, the
  performance of phrase localization is far from satisfactory. In principle, the phrase
  should be easier to localize as fewer combinations of visual concepts need to be
  considered; such incapability indicates that the existing models only capture the
  sentence annotation bias in the benchmark but lack sufficient understanding of the
  intrinsic relationship between simple visual and language concepts, thus the model
  generalization and interpretability is questioned. This paper proposes a unified
  framework that can deal with both sentence and phrase-level localization, namely
  Phrase Level Prediction Net (PLPNet). Specifically, based on the hypothesis that
  similar phrases tend to focus on similar video cues, while dissimilar ones should
  not, we build a contrastive mechanism to restrain phrase-level localization without
  fine-grained phrase boundary annotation required in training. Moreover, considering
  the sentence’s flexibility and wide discrepancy among phrases, we propose a clustering-based
  batch sampler to ensure that contrastive learning can be conducted efficiently.
  Extensive experiments demonstrate that our method surpasses state-of-the-art methods
  of phrase-level temporal localization while maintaining high performance in sentence
  localization and boosting the model’s interpretability and generalization capability.
  Our code is available at https://github.com/sizhelee/PLPNet.
---

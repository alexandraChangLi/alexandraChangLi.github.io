---
title: 'Multi-Ontology Refined Embeddings (MORE): A hybrid multi-ontology and corpus-based
  semantic representation model for biomedical concepts'
authors:
- Steven Jiang
- Weiyi Wu
- Naofumi Tomita
- Craig Ganoe
- Saeed Hassanpour
date: '2020-11-01'
publishDate: '2024-01-15T06:08:03.792385Z'
publication_types:
- article-journal
publication: '*Journal of Biomedical Informatics*'
doi: 10.1016/j.jbi.2020.103581
abstract: 'Objective: Currently, a major limitation for natural language processing
  (NLP) analyses in clinical applications is that concepts are not effectively referenced
  in various forms across different texts. This paper introduces MultiOntology Refined
  Embeddings (MORE), a novel hybrid framework that incorporates domain knowledge from
  multiple ontologies into a distributional semantic model, learned from a corpus
  of clinical text. Materials and Methods: We use the RadCore and MIMIC-III free-text
  datasets for the corpus-based component of MORE. For the ontology-based part, we
  use the Medical Subject Headings (MeSH) ontology and three state-ofthe-art ontology-based
  similarity measures. In our approach, we propose a new learning objective, modified
  from the sigmoid cross-entropy objective function. Results and Discussion: We used
  two established datasets of semantic similarities among biomedical concept pairs
  to evaluate the quality of the generated word embeddings. On the first dataset with
  29 concept pairs, with similarity scores established by physicians and medical coders,
  MORE’s similarity scores have the highest combined correlation (0.633), which is
  5.0% higher than that of the baseline model, and 12.4% higher than that of the best
  ontology-based similarity measure. On the second dataset with 449 concept pairs,
  MORE’s similarity scores have a correlation of 0.481, based on the average of four
  medical residents’ similarity ratings, and that outperforms the skip-gram model
  by 8.1%, and the best ontology measure by 6.9%. Furthermore, MORE out­ performs
  three pre-trained transformer-based word embedding models (i.e., BERT, ClinicalBERT,
  and BioBERT) on both datasets. Conclusion: MORE incorporates knowledge from several
  biomedical ontologies into an existing corpus-based distributional semantics model,
  improving both the accuracy of the learned word embeddings and the extensi­ bility
  of the model to a broader range of biomedical concepts. MORE allows for more accurate
  clustering of concepts across a wide range of applications, such as analyzing patient
  health records to identify subjects with similar pathologies, or integrating heterogeneous
  clinical data to improve interoperability between hospitals.'
links:
- name: URL
  url: https://linkinghub.elsevier.com/retrieve/pii/S1532046420302094
---

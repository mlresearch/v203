---
title: Evaluating the Robustness of Biomedical Concept Normalization
abstract: 'Biomedical concept normalization involves linking entity mentions in text
  to standard concepts in knowledge bases. It aids in resolving challenges to standardising
  ambiguous, variable terms in text or handling missing links. Therefore, it is one
  of the essential tasks of text mining that helps in effective information access
  and finds its utility in biomedical decision-making. Pre-trained language models
  (e.g., BERT) achieve impressive performance on this task. It has been observed that
  such models are insensitive to word order permutations and vulnerable to adversarial
  attacks on tasks like Text Classification, Natural Language Inference. However,
  the effect of such attacks is unknown for the task of Normalization, especially
  in the biomedical domain. In this paper, we propose heuristics-based Input Transformations
  (word level modifications and word order variations) and Adversarial Attacks to
  study the robustness of BERT-based normalization models across various datasets
  consisting of different biomedical entity types. We conduct experiments across three
  datasets: NCBI disease, BC5CDR Disease, and BC5CDR Chemical. We observe that for
  input transformations, pre-trained models often fail to detect invalid input. On
  the other hand, our proposed adversarial attacks that add imperceptible perturbations,
  result in affecting the ranking of a concept list for a given mention (or vice versa).
  We also generate natural adversarial examples that lead to performance degradation
  of  30% in the F1-score. Additionally, we explore existing mitigation strategies
  to help a model recognize invalid inputs.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty23a
month: 0
tex_title: Evaluating the Robustness of Biomedical Concept Normalization
firstpage: 63
lastpage: 73
page: 63-73
order: 63
cycles: false
bibtex_author: Chakraborty, Sinchani and Raj, Harsh and Gureja, Srishti and Jain,
  Tanmay and Hassan, Atif and Basu, Sayantan
author:
- given: Sinchani
  family: Chakraborty
- given: Harsh
  family: Raj
- given: Srishti
  family: Gureja
- given: Tanmay
  family: Jain
- given: Atif
  family: Hassan
- given: Sayantan
  family: Basu
date: 2023-01-19
address:
container-title: Proceedings of The 1st Transfer Learning for Natural Language Processing
  Workshop
volume: '203'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 1
  - 19
pdf: https://proceedings.mlr.press/v203/chakraborty23a/chakraborty23a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

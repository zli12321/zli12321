---
title:          "SODAPOP: Open-ended discovery of social biases in social commonsense reasoning models"
date:           2023-11-07 00:01:00 +0800
selected:       true
pub:            "EACL"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2023"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  A common limitation of diagnostic tests for detecting social biases in NLP models is that they may only detect stereotypic associations that are pre-specified by the designer of the test. Since enumerating all possible problematic associations is infeasible, it is likely these tests fail to detect biases that are present in a model but not pre-specified by the designer. To address this limitation, we propose SODAPOP (SOcial bias Discovery from Answers about PeOPle) in social commonsense question-answering. Our pipeline generates modified instances from the Social IQa dataset (Sap et al., 2019) by (1) substituting names associated with different demographic groups, and (2) generating many distractor answers from a masked language model. By using a social commonsense model to score the generated distractors, we are able to uncover the model's stereotypic associations between demographic groups and an open set of words. We also test SODAPOP on debiased models and show the limitations of multiple state-of-the-art debiasing algorithms.

cover:          /assets/images/covers/sodapop.png
authors:
  - Haozhe An
  - Zongxia Li
  - Jieyu Zhao
  - Rachel Rudinger


links:
  Code: https://github.com/haozhe-an/SODAPOP
  Paper: https://arxiv.org/abs/2210.07269
---

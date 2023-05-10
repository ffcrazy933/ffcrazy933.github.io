---
abstract: Concepts benefit natural language understanding but are far from
  complete in existing knowledge graphs (KGs). Recently, pre-trained language
  models (PLMs) have been widely used in text-based concept extraction (CE).
  However, PLMs tend to mine the co-occurrence associations from massive corpus
  as pre-trained knowledge rather than the real causal effect between tokens. As
  a result, the pre-trained knowledge confounds PLMs to extract biased concepts
  based on spurious co-occurrence correlations, inevitably resulting in low
  precision. In this paper, through the lens of a Structural Causal Model (SCM),
  we propose equipping the PLM-based extractor with a knowledge-guided prompt as
  an intervention to alleviate concept bias. The prompt adopts the topic of the
  given entity from the existing knowledge in KGs to mitigate the spurious
  co-occurrence correlations between entities and biased concepts. Our extensive
  experiments on representative multilingual KG datasets justify that our
  proposed prompt can effectively alleviate concept bias and improve the
  performance of PLM-based CE models.The code has been released on
  https://github.com/siyuyuan/KPCE.
slides: ""
url_pdf: https://arxiv.org/abs/2305.01876
publication_types:
  - "1"
authors:
  - admin
  - Deqing Yang
  - Jinxi Liu
  - Shuyu Tian
  - Jiaqing Liang
  - Yanghua Xiao
  - Rui Xie
author_notes: []
publication: In *The 61th Annual Meeting of the Association for Computational
  Linguistics (**ACL 2023**)*
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Causality-aware Concept Extraction based on Knowledge-guided Prompting
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: 1.png
date: 2023-05-10T02:12:23.523Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: https://github.com/siyuyuan/kpce
---

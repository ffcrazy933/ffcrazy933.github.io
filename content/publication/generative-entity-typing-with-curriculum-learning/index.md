---
abstract: "Entity typing aims to assign types to the entity mentions in given
  texts. The traditional classification-based entity typing paradigm has two
  unignorable drawbacks: 1) it fails to assign an entity to the types beyond the
  predefined type set, and 2) it can hardly handle few-shot and zero-shot
  situations where many long-tail types only have few or even no training
  instances. To overcome these drawbacks, we propose a novel generative entity
  typing (GET) paradigm: given a text with an entity mention, the multiple types
  for the role that the entity plays in the text are generated with a
  pre-trained language model (PLM). However, PLMs tend to generate
  coarse-grained types after fine-tuning upon the entity typing dataset.
  Besides, we only have heterogeneous training data consisting of a small
  portion of human-annotated data and a large portion of auto-generated but
  low-quality data. To tackle these problems, we employ curriculum learning (CL)
  to train our GET model upon the heterogeneous data, where the curriculum could
  be self-adjusted with the self-paced learning according to its comprehension
  of the type granularity and data heterogeneity. Our extensive experiments upon
  the datasets of different languages and downstream tasks justify the
  superiority of our GET model over the state-of-the-art entity typing models.
  The code has been released on https://github.com/siyuyuan/GET."
slides: ""
url_pdf: https://arxiv.org/abs/2210.02914
publication_types:
  - "1"
authors:
  - admin
  - Deqing Yang
  - Jiaqing Liang
  - Zhixu Li
  - Jinxi Liu
  - Jingyue Huang
  - Yanghua Xiao Long paper
author_notes: []
publication: In *The 2022 Conference on Empirical Methods in Natural Language
  Processing(**EMNLP 2022**)*
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Generative Entity Typing with Curriculum Learning
doi: ""
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: 3.png
date: 2022-12-07T02:12:23.523Z
url_slides: https://siyuyuan.github.io/files/GET.pdf
publishDate: 2017-01-01T00:00:00.000Z
url_poster: https://siyuyuan.github.io/files/GET_poster_long.pdf
url_code: https://github.com/siyuyuan/GET
---

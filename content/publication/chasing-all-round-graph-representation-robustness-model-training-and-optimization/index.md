---
title: "Chasing All-Round Graph Representation Robustness: Model, Training, and
  Optimization"
publication_types:
  - "1"
authors:
  - Chunhui Zhang
  - Yijun Tian
  - Mingxuan Ju
  - admin
  - Yanfang Ye
  - Nitesh Chawla
  - and Chuxu Zhang
author_notes: []
publication: ICLR 2023
abstract: "Graph Neural Networks (GNNs) have achieved state-of-the-art results
  on a variety of graph learning tasks, however, it has been demonstrated that
  they are vulnerable to adversarial attacks, raising serious security concerns.
  A lot of studies have been developed to train GNNs in a noisy environment and
  increase their robustness against adversarial attacks. However, existing
  methods have not uncovered a principled difficulty: the convoluted mixture
  distribution between clean and attacked data samples, which leads to
  sub-optimal model design and limits their frameworks’ robustness. In this
  work, we first begin by identifying the root cause of mixture distribution,
  then, for tackling it, we propose a novel method GAME - Graph Adversarial
  Mixture of Experts to enlarge the model capacity and enrich the representation
  diversity of adversarial samples, from three perspectives of model, training,
  and optimization. Specifically, we first propose a plug-and-play GAME layer
  that can be easily incorporated into any GNNs and enhance their adversarial
  learning capabilities. Second, we design a decoupling-based graph adversarial
  training in which the component of the model used to generate adversarial
  graphs is separated from the component used to update weights. Third, we
  introduce a graph diversity regularization that enables the model to learn
  diverse representation and further improves model performance. Extensive
  experiments demonstrate the effectiveness and advantages of GAME over the
  state-of-the-art adversarial training methods across various datasets given
  different attacks."
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
summary: >-
  In this paper, we first identify the fundamental issue in adversarial graph
  learning: the mixture dis-

  tribution between clean and attacked data samples. Motivated by this problem, we propose Graph

  Adversarial Mixture of Experts (GAME), a novel method to improve the model capacity, augment

  adversarial graphs, and enrich the graph representation diversity. For acquiring these triple im-

  provements, GAME contains three innovative components, including a plug-and-play GAME layer,

  a decoupling graph adversarial training strategy DECOG, and a graph diversity regularization strat-

  egy GRADIV. GAME outperforms other baselines when evaluated on several datasets given different attack methods. Additional experimental analyses prove the effectiveness of GAME in handling the

  complex mixture distribution, generating distinct adversarial graphs, and learning distinguishable

  representations.
date: 2023-01-24T15:02:44.939Z
---
H﻿ere is the [link ](https://openreview.net/forum?id=7jk5gWjC18M)to the paper.
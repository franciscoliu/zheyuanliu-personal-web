---
title: "G-Fame: Fair Graph Representation Learning via Diverse Mixture of Experts"
publication_types:
  - "1"
authors:
  - admin*
  - Chunhui Zhang*
  - Yijun Tian
  - Erchi Zhang
  - Chao Huang
  - Yanfang Ye and Chuxu Zhang
publication: International World Wide Web Conference
publication_short: WWW 2023
abstract: >-
  Graph Neural Networks (GNNs) have demonstrated a great representation learning
  capability on graph data and have been utilized in various downstream
  applications. However, real-world data in web-based applications (e.g.,
  recommendation and advertising) always contains bias, preventing GNNs from
  learning fair representations. Although many works were proposed to address
  the fairness issue, they suffer from the significant problem of insufficient
  learnable knowledge with limited attributes after debiasing. To address this
  problem, we develop Graph-Fairness Mixture of Experts (G-Fame), a novel
  plug-and-play method to assist any GNNs to learn discriminative
  representations with unbiased attributes. Furthermore, based on G-Fame, we
  propose G-Fame++, which introduces three novel strategies to improve the
  representation fairness from node representations, model layer, and parameter
  redundancy perspectives. In particular, we first present the embedding
  diversified method

  to learn discriminative node representations. Second, we design the layer diversified strategy to maximize the output difference of distinct model layers. Third, we introduce the expert diversified

  method to minimize expert parameter similarities to learn diverse and complementary representations. Extensive experiments demonstrate the superiority of G-Fame and G-Fame++ in both accuracy and fairness, compared to state-of-the-art methods across multiple graph datasets.
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
summary: >-
  In this paper, we identify the problem of limited learnable information
  problem in graph fairness learning. To address this problem, we present
  G-Fame, a novel plug-and-play method for assisting any

  GNNs to learn discriminative representations. Specifically, G-Fame introduces an MoE mechanism that utilizes multiple expert neural networks to capture different aspects of knowledge in the fairness

  setting. In addition, we propose G-Fame++ with three innovative regularization strategies to further increase the diversity from perspectives of node representations, layers, and experts. Extensive

  experiments and in-depth studies demonstrate the superiority of G-Fame and G-Fame++ across a variety of accuracy and fairness metrics on multiple benchmark datasets.
date: 2023-01-26T02:43:25.178Z
---

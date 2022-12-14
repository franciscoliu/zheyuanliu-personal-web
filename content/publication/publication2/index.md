---
title: "GraphBERT: Bridging Graph and Text for Malicious Behavior Detection on
  Social Media"
publication_types:
  - "1"
authors:
  - Jiele Wu
  - Chunhui Zhang
  - admin
  - Erchi Zhang
  - Steven Wilson
  - and Chuxu Zhang
publication: ICDM 2022
abstract: >-
  The development of social media (e.g., Twitter)

  allows users to make speeches with low cost and broad influence. Thus, social media has become a perfect place for

  users’ malicious behaviors like committing hate crimes, spreading

  toxic information, abetting crimes, etc. Malicious behaviors are

  covert and widespread, with potential relevance regarding topic,

  person, place, and so on. Therefore, it is necessary to develop

  novel techniques to detect and disrupt malicious behavior on

  social media effectively. Previous research has shown promising

  results in extracting semantic text (speech) representation using

  natural language processing methods. Yet the latent relation

  between speeches and the connection between users behind

  speeches is rarely explored. In light of this, we propose a holistic

  model named Graph adaption BERT (GraphBERT) to detect

  malicious behaviors on Twitter with both semantic and relational

  information. Specifically, we first present a novel and a largescale corpus of tweet data to benefit both graph-based and

  language-based malicious behavior detection research. Then, we

  design a novel model GraphBERT to learn comprehensive tweet

  and user representation with the integration of both semantic

  information encoded by transformers (i.e., BERT) and relational

  information encoded by graph neural network. GraphBERT

  further leverages a weight adaption BERT module implemented

  between transformer layers to refine tweet embedding using

  relational information for malicious tweet classification. Finally,

  the adapted tweet embedding is used with the initial tweet

  representation to generate user embedding for malicious user

  detection. The extensive experiments on the collected Twitter data

  show that our model outperforms the state-of-the-art baseline

  methods for both tasks (i.e., malicious tweet classification and

  malicious user detection).
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
summary: |-
  In this paper, we reveal the necessity of malicious behavior
  detection on social media and propose a dataset with both user
  and tweet labels for this research. To integrate both structural
  and semantic information, we create a graph with multiple
  nodes including users, tweets, mentions, hashtags, topics, and
  multiple-name entities. Based on the graph data, we introduce
  a novel GraphBERT model which integrates both semantic
  and relational information.
date: 2022-09-01T19:54:54.830Z
---
H﻿ere is the [link ](https://aragakiyuiii.github.io/data/GraphBERT-%20Bridging%20Graph%20and%20Text%20for%20Malicious%20Behavior%20Detection%20on%20Social%20Media-ICDM22.pdf)to the paper, the conference version is TBD.

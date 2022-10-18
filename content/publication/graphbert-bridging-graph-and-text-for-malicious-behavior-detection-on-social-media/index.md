---
title: "GraphBERT: Bridging Graph and Text for Malicious Behavior Detection on
  Social Media"
publication_types:
  - "1"
authors:
  - Jiele Wu
  - Chunhui Zhang
  - Zheyuan Liu
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
featured: false
image:
  filename: icdm22.png
  focal_point: Smart
  preview_only: false
date: 2022-09-01T19:54:54.830Z
---

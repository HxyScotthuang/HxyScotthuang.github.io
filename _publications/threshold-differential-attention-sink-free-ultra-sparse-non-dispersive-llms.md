---
title: "Threshold Differential Attention for Sink-Free, Ultra-Sparse, and Non-Dispersive Language Modeling"
collection: publications
permalink: https://arxiv.org/abs/2601.12145
excerpt: "Threshold Differential Attention (TDA) is a sink-free attention mechanism that achieves ultra-sparsity and improved robustness at longer sequence lengths without the computational overhead of projection methods or the performance degradation caused by noise accumulation of standard rectified attention."
date: 2026-01-17
venue: 'ACL 2026'
slidesurl: 'https://arxiv.org/abs/2601.12145'
paperurl: 'https://arxiv.org/pdf/2601.12145'
citation: 'X Huang, X Ding, M Ju, Y Liu, N Shah, T Zhao, Threshold Differential Attention for Sink-Free, Ultra-Sparse, and Non-Dispersive Language Modeling, ACL 2026'
authors:
  - "Xingyue Huang"
  - "Xueying Ding"
  - "Mingxuan Ju"
  - "Yozen Liu"
  - "Neil Shah"
  - "Tong Zhao"
categories:
  - "Machine Learning"
tags:
  - "Attention Mechanisms"
  - "Long Context"
  - "Sparse Attention"
---

Softmax attention struggles with long contexts due to structural limitations: the strict sum-to-one constraint forces attention sinks on irrelevant tokens, and probability mass disperses as sequence lengths increase. We tackle these problems with Threshold Differential Attention (TDA), a sink-free attention mechanism that achieves ultra-sparsity and improved robustness at longer sequence lengths without the computational overhead of projection methods or the performance degradation caused by noise accumulation of standard rectified attention. TDA applies row-wise extreme-value thresholding with a length-dependent gate, retaining only exceedances. Inspired by the differential transformer, TDA also subtracts an inhibitory view to enhance expressivity. Theoretically, we prove that TDA controls the expected number of spurious survivors per row to O(1) and that consensus spurious matches across independent views vanish as context grows. Empirically, TDA produces >99% exact zeros and eliminates attention sinks while maintaining competitive performance on standard and long-context benchmarks.


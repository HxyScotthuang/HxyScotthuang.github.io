---
title: "Hierarchical Token Prepending: Enhancing Information Flow in Decoder-based LLM Embeddings"
collection: publications
permalink: https://arxiv.org/abs/2511.14868
excerpt: "Hierarchical Token Prepending (HTP) partitions the input into blocks and prepends block-level summary tokens to subsequent blocks, creating multiple pathways for backward information flow, achieving consistent performance gains across 11 retrieval datasets and 30 general embedding benchmarks."
date: 2025-11-18
venue: 'Under Review'
slidesurl: 'https://arxiv.org/abs/2511.14868'
paperurl: 'https://arxiv.org/pdf/2511.14868'
citation: 'X Ding, X Huang, M Ju, L Collins, Y Liu, L Akoglu, N Shah, T Zhao, Hierarchical Token Prepending: Enhancing Information Flow in Decoder-based LLM Embeddings, arXiv:2511.14868, 2025'
authors:
  - "Xueying Ding"
  - "Xingyue Huang"
  - "Mingxuan Ju"
  - "Liam Collins"
  - "Yozen Liu"
  - "Leman Akoglu"
  - "Neil Shah"
  - "Tong Zhao"
categories:
  - "Machine Learning"
tags:
  - "LLM Embeddings"
  - "Long Context"
  - "Information Flow"
---

Large language models produce powerful text embeddings, but their causal attention mechanism restricts the flow of information from later to earlier tokens, degrading representation quality. While recent methods attempt to solve this by prepending a single summary token, they over-compress information, hence harming performance on long documents. We propose Hierarchical Token Prepending (HTP), a method that resolves two critical bottlenecks. To mitigate attention-level compression, HTP partitions the input into blocks and prepends block-level summary tokens to subsequent blocks, creating multiple pathways for backward information flow. To address readout-level over-squashing, we replace last-token pooling with mean-pooling, a choice supported by theoretical analysis. HTP achieves consistent performance gains across 11 retrieval datasets and 30 general embedding benchmarks, especially in long-context settings. As a simple, architecture-agnostic method, HTP enhances both zero-shot and finetuned models, offering a scalable route to superior long-document embeddings.


---
title: "Flock: A Knowledge Graph Foundation Model via Learning on Random Walks"
collection: publications
permalink: https://arxiv.org/abs/2510.01510
excerpt: "Flock introduces probabilistic node–relation equivariance and learns from random walks to achieve strong zero-shot link prediction across diverse knowledge graphs."
date: 2025-10-01
venue: 'arXiv'
slidesurl: 'https://arxiv.org/abs/2510.01510'
paperurl: 'https://arxiv.org/pdf/2510.01510'
citation: 'J Kim, X Huang, K Olejniczak, K Min, M Bronstein, S Hong, İİ Ceylan, Flock: A Knowledge Graph Foundation Model via Learning on Random Walks, arXiv:2510.01510, 2025'
authors:
  - "Jinwoo Kim"
  - "Xingyue Huang"
  - "Krzysztof Olejniczak"
  - "Kyungbin Min"
  - "Michael Bronstein"
  - "Seunghoon Hong"
  - "İsmail İlkan Ceylan"
categories:
  - "Machine Learning"
tags:
  - "Knowledge Graphs"
  - "Foundation Models"
---

We study the problem of zero-shot link prediction on knowledge graphs (KGs), which requires models to generalize over novel entities and novel relations. Knowledge graph foundation models (KGFMs) address this task by enforcing equivariance over both nodes and relations, learning from structural properties of nodes and relations, which are then transferable to novel graphs with similar structural properties. However, the conventional notion of deterministic equivariance imposes inherent limits on the expressive power of KGFMs, preventing them from distinguishing structurally similar but semantically distinct relations. To overcome this limitation, we introduce probabilistic node-relation equivariance, which preserves equivariance in distribution while incorporating a principled randomization to break symmetries during inference. Building on this principle, we present Flock, a KGFM that iteratively samples random walks, encodes them into sequences via a recording protocol, embeds them with a sequence model, and aggregates representations of nodes and relations via learned pooling. Crucially, Flock respects probabilistic node-relation equivariance and is a universal approximator for isomorphism-invariant link-level functions over KGs. Empirically, Flock perfectly solves our new diagnostic dataset Petals where current KGFMs fail, and achieves state-of-the-art performances on entity- and relation prediction tasks on 54 KGs from diverse domains.



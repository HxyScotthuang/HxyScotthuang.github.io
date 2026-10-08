---
title: "To Learn is to Wander: Learning Across Graphs and Tasks with Random Walks"
collection: publications
permalink: https://arxiv.org/abs/2610.06694
excerpt: "Wander is a graph foundation model that uses random walks to transfer across graphs, feature spaces, relational schemas, and prediction tasks from a single pretrained checkpoint."
date: 2026-10-06
venue: 'arXiv'
slidesurl: 'https://arxiv.org/abs/2610.06694'
paperurl: 'https://arxiv.org/pdf/2610.06694'
citation: 'L Tichelman, X Huang, J Kim, İİ Ceylan, To Learn is to Wander: Learning Across Graphs and Tasks with Random Walks, arXiv preprint arXiv:2610.06694, 2026'
authors:
  - "Louis Tichelman"
  - "Xingyue Huang"
  - "Jinwoo Kim"
  - "İsmail İlkan Ceylan"
categories:
  - "Machine Learning"
tags:
  - "Graph Foundation Models"
  - "Random Walks"
---

Graph foundation models aim to transfer across graphs, feature spaces, relational schemas, and prediction tasks, yet existing approaches typically generalize only within particular graph modalities or tasks. We propose Wander, a graph foundation model designed to operate across these settings within a single pretrained checkpoint. Following the prior-predictive perspective, we formulate graph learning as completion of a partially observed graph. We realize this task-general view through a common interface based on random walks, allowing the same model to operate across homogeneous and multi-relational graphs with varying features, labels, and relational schemas. Wander can increase its structural context at inference time without changing its learned parameters and, under suitable assumptions, universally approximates the corresponding Bayes-optimal predictor on bounded connected graphs. Empirically, a single pretrained checkpoint achieves state-of-the-art or highly competitive results across node classification, homogeneous link prediction, and knowledge-graph link prediction. Moreover, joint pretraining across graph modalities and tasks preserves performance in specialized settings while enabling positive transfer and the composition of separately learned capabilities at inference time.

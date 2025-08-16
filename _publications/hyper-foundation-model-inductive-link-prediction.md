---
title: "HYPER: A Foundation Model for Inductive Link Prediction with Knowledge Hypergraphs"
collection: publications
type: "paper"
permalink: https://arxiv.org/abs/2506.12362
venue: "arXiv preprint"
date: 2025-06-14
authors: Xingyue Huang, Mikhail Galkin, Michael M. Bronstein, İsmail İlkan Ceylan
---

Inductive link prediction with knowledge hypergraphs is the task of predicting missing hyperedges involving completely novel entities (i.e., nodes unseen during training). Existing methods for inductive link prediction with knowledge hypergraphs assume a fixed relational vocabulary and, as a result, cannot generalize to knowledge hypergraphs with novel relation types (i.e., relations unseen during training). Inspired by knowledge graph foundation models, we propose HYPER as a foundation model for link prediction, which can generalize to any knowledge hypergraph, including novel entities and novel relations. Importantly, HYPER can learn and transfer across different relation types of varying arities, by encoding the entities of each hyperedge along with their respective positions in the hyperedge. To evaluate HYPER, we construct 16 new inductive datasets from existing knowledge hypergraphs, covering a diverse range of relation types of varying arities. Empirically, HYPER consistently outperforms all existing methods in both node-only and node-and-relation inductive settings, showing strong generalization to unseen, higher-arity relational structures.

**Subjects:** Machine Learning (cs.LG); Artificial Intelligence (cs.AI)

**Cite as:** arXiv:2506.12362 [cs.LG]

**Submitted on 14 Jun 2025**

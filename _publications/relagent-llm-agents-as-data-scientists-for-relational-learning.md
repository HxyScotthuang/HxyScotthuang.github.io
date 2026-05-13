---
title: "RelAgent: LLM Agents as Data Scientists for Relational Learning"
collection: publications
permalink: https://arxiv.org/abs/2605.07840
excerpt: "RelAgent is an LLM-based autonomous data scientist for relational learning that searches over SQL feature programs and predictive models, then deploys fast, deterministic, and interpretable predictors without LLM calls at inference time."
date: 2026-05-08
venue: 'arXiv'
slidesurl: 'https://arxiv.org/abs/2605.07840'
paperurl: 'https://arxiv.org/pdf/2605.07840'
citation: 'X Huang, L Tichelman, J Kim, K Olejniczak, İİ Ceylan, RelAgent: LLM Agents as Data Scientists for Relational Learning, arXiv:2605.07840, 2026'
authors:
  - "Xingyue Huang"
  - "Louis Tichelman"
  - "Jinwoo Kim"
  - "Krzysztof Olejniczak"
  - "İsmail İlkan Ceylan"
categories:
  - "Machine Learning"
tags:
  - "Relational Learning"
  - "LLM Agents"
  - "SQL"
---

Relational learning is a challenging problem that has motivated a wide range of approaches, including graph-based models, tabular methods, and sequence-based approaches, each with its own advantages and limitations. We propose RelAgent, an LLM-based autonomous data scientist for relational learning, which operates in two phases. In the search phase, an LLM agent uses database, validation, and evaluation workspace tools to construct SQL feature programs and select a predictive model. In the inference phase, the resulting program is executed without further LLM calls. The final predictor consists of SQL queries and a classical model, enabling fast, deterministic, and intrinsically interpretable predictions: features are human-readable queries, and predictions depend only on the resulting query-defined feature map, enabling scalable deployment using standard database systems.


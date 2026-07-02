---
title: "What are the Right Symmetries for Formal Theorem Proving?"
collection: publications
permalink: https://arxiv.org/abs/2605.22257
excerpt: "Introduces rewriting categories to formalize proof equivariance and success invariance for formal theorem proving, and proposes test-time ensembling methods that improve robustness of LLM-based provers."
date: 2026-05-28
venue: 'ICML AI for Math Workshop'
slidesurl: 'https://arxiv.org/abs/2605.22257'
paperurl: 'https://arxiv.org/pdf/2605.22257'
citation: 'K Olejniczak, R Dimitrov, X Huang, B Cuenca Grau, J Kim, İİ Ceylan, What are the Right Symmetries for Formal Theorem Proving?, AI for Math Workshop at ICML, 2026'
authors:
  - "Krzysztof Olejniczak"
  - "Radoslav Dimitrov"
  - "Xingyue Huang"
  - "Bernardo Cuenca Grau"
  - "Jinwoo Kim"
  - "İsmail İlkan Ceylan"
categories:
  - "Machine Learning"
tags:
  - "Theorem Proving"
  - "Formal Methods"
  - "Symmetry"
---

Formal theorem provers based on large language models (LLMs) are highly sensitive to superficial variations in problem representation: semantically equivalent statements can exhibit drastically different proof success rates, revealing a failure to respect structural symmetries inherent in formal mathematics. We introduce rewriting categories, a category-theoretic framework capturing the compositional, generally non-invertible transformations induced by proof tactics, and use it to formalize two symmetry notions: proof equivariance and success invariance. We propose test-time methods that aggregate over equivalent rewritings of the input, showing theoretically that they recover success invariance in the sampling limit, and empirically, that they improve robustness and performance under fixed inference budgets.

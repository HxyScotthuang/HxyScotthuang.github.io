---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
You can also download my CV [here](CV_Xingyue_Huang.pdf)!

Xingyue Huang  
Tel: (44) 7579 902135  
Email: xingyue.huang@cs.ox.ac.uk  
Website: [https://hxyscotthuang.github.io/](https://hxyscotthuang.github.io/)

Education
======
* **University of Oxford**  
  DPhil in Computer Science (2023 – 2026)  
  Advisors: Prof. Michael Bronstein (DeepMind Chair of AI), Prof. Ismail Ceylan
* **University of Oxford**  
  MMathCompSci in Mathematics and Computer Science (2019 – 2023)  
  Graduated with Distinction

Professional Experience
======

* **Meta Platforms Inc.**  
  Research Scientist Intern (06/2026 – 09/2026)
  * Developed an LLM-based survey imputation system for advertiser campaign measurement, modeling responses from 5k advertisers across 18 questions and 10 weekly waves.
  * Reduced aggregate distributional error by 3.4×, from 26.3% to 7.8%, using quantile-mapped KNN on Llama 4.
  * Designed LLM-XGBoost ensemble methods achieving the best distributional fidelity, reducing PPE to 6.7% and improving accuracy by 1.7% by using LLM predictions as tabular features.

* **AITHYRA Research Institute for Biomedical Artificial Intelligence**  
  Predoctoral Fellow (03/2026 – 05/2026)
  * Developed RelAgent, an LLM-based autonomous data scientist that searches over SQL feature programs and model choices for relational learning.
  * Achieved rank 1.00 on RelBenchV2 and 4DBInfer classification benchmarks, improving average AUROC over KumoRFM-v2 from 85.91 to 87.32 and from 79.96 to 81.38, respectively.
  * Designed deterministic inference without further LLM calls, yielding interpretable SQL-defined feature maps paired with classical predictors for scalable database deployment.

* **Snap Inc.**  
  Research Intern (06/2025 – 10/2025)
  * Developed Threshold Differential Attention (TDA), a sink-free, ultra-sparse attention mechanism for long-context LLMs, achieving >99% exact zeros while matching Softmax accuracy on QA benchmarks.
  * Pre-trained large language models from scratch and demonstrated long-context robustness on SCROLLS passkey retrieval, where TDA outperformed Softmax by approximately 2.5× at 4k-token contexts.
  * Co-authored Hierarchical Token Prepending, improving long-document embeddings in decoder-only LLMs via block-level summary tokens, with 5% gains across 11 retrieval datasets and 30 embedding benchmarks.

* **Eigent-AI**  
  Research Intern (10/2024 – 06/2025)
  * Built a tool-use synthetic data generation pipeline producing 20k verified execution traces for CAMEL-AI.
  * Used back-translated tool trajectories for supervised fine-tuning, improving math benchmark accuracy by 5%.
  * Led the Loong verifier-driven RL framework for long chain-of-thought synthesis.

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards
======
* Oriel Student Scholarships for Academic Merit (2021 – 2023)
* NeurIPS 2025 Top Reviewer Award
* ICML 2026 Silver Reviewer Award

Service
======
* Reviewer: NeurIPS 2025 · ICML 2026 · ICLR 2026
* Lead Organizer: Workshop on Graph Foundation Models, ICML 2026
* Organizer: Scaling Environment of Agents (SEA) Workshop, NeurIPS 2025
* Invited Talks:
  * RelAgent: LLM Agents as Data Scientists for Relational Learning — Stanford University; CAMEL-AI
  * Graph Foundation Models Tutorial — Learning on Graphs 2025
  * How Expressive are Knowledge Graph Foundation Models? — Snap Inc., 2025
  * Relational Hypergraphs for Knowledge Graph Foundation Models — TU Wien, 2026

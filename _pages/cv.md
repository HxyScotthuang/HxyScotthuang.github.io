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

* **Snap Inc.**  
  Research Intern (UMaP) (06/2025 – 10/2025)
  * Developed Threshold Differential Attention (TDA), a sink-free, ultra-sparse attention mechanism for long-context LLMs, achieving >99% exact zeros while matching Softmax accuracy on QA benchmarks.
  * Demonstrated long-context robustness on the SCROLLS benchmark and passkey-retrieval stress tests, where TDA outperformed Softmax by ~2.5× at 4k-token contexts.
  * Co-authored Hierarchical Token Prepending, improving long-document embeddings in decoder-only LLMs via block-level summary tokens, with 5% gains across 11 retrieval datasets and 30 embedding benchmarks.

* **Eigent-AI**  
  Research Intern (10/2024 – 06/2025)
  * Built a tool-use synthetic data generation pipeline producing 20k verified execution traces for CAMEL-AI.
  * Used back-translated tool trajectories for supervised fine-tuning, improving math benchmark accuracy by 5%.
  * Led the Loong verifier-driven RL framework for long chain-of-thought synthesis.

* **Alibaba Group**  
  Machine Learning Engineer Intern (07/2021 – 09/2021)
  * Developed an object detection system for video subtitle-detection with Faster-RCNN model.
  * Improved accuracy of object detection and classification by 10% and were incorporated into production.

Technical Skills
======
* Systems & Infrastructure: Triton, LLM architecture design, multi-agent systems, post-training
* ML & Data: PyTorch, HuggingFace, CAMEL-AI, SQL, DuckDB, pandas, torch-geometric

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Services
======
* Reviewer: NeurIPS 2025 Top Reviewer · ICML 2026 Silver Reviewer · ICLR 2026
* Workshop Organizer: NeurIPS 2025 SEA, ICML 2026 GFM
* Talks: Tutorial on Graph Foundation Models (LoG 2025) · Relational Hypergraphs (TU Wien Guest Lecture on GRL 2026/03/19, LoG 2024 Oxford Meetup)


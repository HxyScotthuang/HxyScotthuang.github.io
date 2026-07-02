---
permalink: /
title: "Welcome to Xingyue Huang's Personal Website"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! 👋

I'm **Xingyue Huang (黄星越)**, a DPhil student in Computer Science at the University of Oxford, supervised by [Prof. Michael M. Bronstein](https://www.cs.ox.ac.uk/people/michael.bronstein/) and [Dr. İsmail İlkan Ceylan](https://www.cs.ox.ac.uk/people/ismaililkan.ceylan/). My work focuses on **language models**, **AI agents**, and **foundation models**, with an emphasis on structured reasoning and generalization.

I work on language model pre-training, long-context modeling, and efficient attention, as well as agent systems and architectures for tool-using, reasoning-oriented AI. My research background is in **graph machine learning**, **knowledge graphs**, and **relational learning** — studying how models reason over structured data and generalize to new entities, relations, and tasks.

My work has been published at **ACL**, **NeurIPS**, **ICML**, and **ICLR**. I'm especially interested in building LLM-based systems that reason reliably and use context effectively, and I'm open to connecting with people working on language models, agents, foundation models, and applied AI.

**Research interests:** Large Language Models, AI Agents, Foundation Models, Long-Context Modeling, Structured Reasoning, Retrieval-Augmented Generation, Knowledge Graphs, Graph Neural Networks, Relational Learning.

---

## 📰 News

{% assign news = site.portfolio | sort: 'date' | reverse %}
{% for post in news %}
  {% include archive-single.html %}
{% endfor %}

## 🛠️ Service
- Reviewer: **NeurIPS 2025 Top Reviewer**, **ICML 2026 Silver Reviewer**, **ICLR 2026**
- Workshop Organizer: **NeurIPS 2025 SEA**, **ICML 2026 GFM**

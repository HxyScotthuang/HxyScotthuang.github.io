---
title: "Cooperative graph neural networks"
collection: publications
permalink: _publications\cooperative-graph-neural-networks.md
excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2024-05-01
venue: 'ICML'
slidesurl: 'https://arxiv.org/abs/2310.01267'
paperurl: 'https://arxiv.org/pdf/2310.01267'
citation: 'B Finkelshtein, X Huang, M Bronstein, İİ Ceylan, Cooperative graph neural networks, arXiv preprint arXiv:2310.01267, 2023'
---

Graph neural networks are popular architectures for graph machine learning, based on iterative computation of node representations of an input graph through a series of invariant transformations. A large class of graph neural networks follow a standard message-passing paradigm: at every layer, each node state is updated based on an aggregate of messages from its neighborhood. In this work, we propose a novel framework for training graph neural networks, where every node is viewed as a player that can choose to either 'listen', 'broadcast', 'listen and broadcast', or to 'isolate'. The standard message propagation scheme can then be viewed as a special case of this framework where every node 'listens and broadcasts' to all neighbors. Our approach offers a more flexible and dynamic message-passing paradigm, where each node can determine its own strategy based on their state, effectively exploring the graph topology while learning. We provide a theoretical analysis of the new message-passing scheme which is further supported by an extensive empirical analysis on a synthetic dataset and on real-world datasets.
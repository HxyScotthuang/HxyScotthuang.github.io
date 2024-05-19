---
title: 'Cooperative Graph Neural Networks'
date: 2023-12-16
permalink: https://lnkd.in/eWNZSgHt
tags:
  - graph representation learning
  - graph neural networks
  - geometric deep learning
---


A large majority of Graph Neural Networks (GNNs) follow the message-passing paradigm, where node states are updated based on aggregated neighbour messages. In this post, we describe Co-operative GNNs (Co-GNNs), a new type of message-passing architecture where every node is viewed as a player that can choose to either ‘listen’, ‘broadcast’, ‘listen & broadcast’, or to ‘isolate.’ Standard message passing is a special case where every node ‘listens & broadcasts’ to all neighbours. We show that Co-GNNs are asynchronous, more expressive, and can address common plights of standard message-passing GNNs such as over-squashing and over-smoothing.


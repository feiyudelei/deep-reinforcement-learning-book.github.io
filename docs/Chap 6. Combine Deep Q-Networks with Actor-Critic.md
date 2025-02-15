---
layout: default
title: Chap 6. Combine Deep Q-Networks with Actor-Critic
nav_order: 6
---

## Authors

- Hongming Zhang* - Peking University (zhanghongming[at]pku.edu.cn)
- Tianyang Yu - Nanchang University
- Ruitong Huang - Borealis AI

## Abstract

The deep Q-network algorithm is one of the most well-known deep reinforcement learning algorithms, which combines reinforcement learning with deep neural networks to approximate the optimal action-value functions. It receives only the pixels as inputs and achieves human-level performance on Atari games. Actor-critic methods transform the Monte Carlo update of the REINFORCE algorithm into the temporal-difference update for learning the policy parameters. Recently, some algorithms that combine deep Q-networks with actor-critic methods such as the deep deterministic policy gradient algorithm are very popular. These algorithms take advantages of both methods and perform well in most environments especially with continuous action spaces. In this chapter, we give a brief introduction of the advantages and disadvantages of each kind of algorithm, then introduce some classical methods that combine deep Q-networks and actor-critic like the deep deterministic policy gradient algorithm, the twin delayed deep deterministic policy gradient algorithm and the soft actor-critic algorithm.

**Keywords**: deep Q-network, actor-critic, deep deterministic policy gradient, twin delayed deep deterministic policy gradient, soft actor-critic

## Content
[中文版PDF](/assets/pdfs/ch6.pdf){: .btn .btn-purple  .fs-3 .mb-4 .mb-md-0 .mr-2 }

## Code 

Codes for contents in this chapter are available [**here**](https://github.com/tensorlayer/tensorlayer/tree/master/examples/reinforcement\_learning).

## Citation

To cite this book, please use this bibtex entry:

```
@incollection{deepRL-chapter6-2020,
 title={Combine Deep Q-Networks with Actor-Critic},
 chapter={6},
 author={Hongming Zhang, Tianyang Yu, Ruitong Huang},
 editor={Hao Dong, Zihan Ding, Shanghang Zhang},
 booktitle={Deep Reinforcement Learning: Fundamentals, Research, and Applications},
 publisher={Springer Nature},
 pages={213-248},
 note={\url{http://www.deepreinforcementlearningbook.org}},
 year={2020}
}
```





If you find any typos or have suggestions for improving the book, do not hesitate to contact with the corresponding author (name with *).
---
layout: archive
title: ""
permalink: /algorithmic-game-theory/
author_profile: true
---

Matching on Social Networks
------
My research topic is mechanism design for one-sided matching over social networks. Mechanism design is an intersection of computer science and economics. In this field, we design algorithms in a game theoretic environment, where the agents who provide the inputs are also the recipients of the algorithm. Naturally, these agents have incentives to misreport their private data to get better results. They may even refuse to get involved if the algorithm is against their interests. Therefore, our goal is to design Individual Rational (IR) and Incentive Compatible (IC) mechanisms, which means our mechanisms incentivize agents to join the game and reveal true data. My focus is one-sided matching: a group of agents each has an initial endowment, and they exchange with each other to get a better one. An ideal algorithm should incentivize agents to join the matching and reveal their true preferences. Two key properties to evaluate a matching are stable and optimal. The former requires that no group of agents wants to deviate and match among themselves, and the latter means no agent can improve her matching without making others worse. The well-known Top Trading Cycle (TTC) mechanism gives the unique IR, IC, stable, and optimal solution. 

In matching, an interesting observation is that more agents joining in the matching provides more selections. With the increase of possible selections, the matching result is more promising in expectation. Several real-world applications, like [online housing markets](https://www.homeexchange.com) and [second-hand goods exchange platforms](https://www.freecycle.org), have utilized social networks to promote their market. In these platforms, existing participants propagate the information to their friends to form larger markets. But sometimes participants may hesitate to propagate because their friends will compete with them in the matching game. For this reason, the main obstacle is to assure participants that inviting all their friends to join the matching is not harmful. Our goal is to model this market expansion in matching and design mechanisms to incentivize agents to reveal true preferences and invite all their neighbors to join the matching. 


In this new setting, TTC fails to be IC. To design incentives, one intuitive idea is to constrain participants’ selection space thus removing potential competition caused by invitation. For example, restrict that participants can only exchange with their neighbors so that invitation is never harmful. Yet, such restrictions also hinder better allocation for invitees who will not harm their inviters, sacrificing overall efficiency. The challenge is that we cannot tell whether an agent’s invitation will harm herself or those who invited her without fixing a matching mechanism. It seems that a natural way to find a better mechanism is through trial and error. However, this is not feasible in practice since the space and description of the mechanism are exponential in the number of participants. To get a better matching, we need to distinguish the incentive compatible cycles and let them trade. 


The goals are summarized as follows:
1. Construct a model to formalize one-sided matching over social networks. Define the key properties like IR, IC, stable, and optimal in the network setting. 
2. Design IC matching mechanisms in the network setting. 
3. TTC is the boundary for traditional one-sided matching, but it fails IC in the network setting. We need to construct new theoretical boundaries (the tightest stability and optimality we can achieve with IC) in the network setting. 
4. Compare and analyze the performance of all the IC mechanisms in theory and simulations.

<!-- Networked Games
------ -->





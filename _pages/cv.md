---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
------
* M.S. in Computer Science and Technology, ShanghaiTech University, 2021-2024 (expected)
* B.S. in Software Engineering, A Joint Program of Beihang University and Beijing University of Technology, 2017-2021

Publication
------
* Truthful and Stable One-sided Matching on Networks.（Accepted by AAMAS2024 as Extended Abstract.)
We design the first incentive compatible solutions for matching on networks (without restriction on the network structure). Despite theoretical analysis, we conduct simulations to compare the average agent’s satisfaction under different solutions.

* Optimal One-sided Matching on Networks. (Under Review)
This work constructs the theoretical boundaries for one-sided matching on networks and proposes a mechanism called
Connected Trading Cycles to reach them. Specifically, we redefine the optimality notion and prove the implication between
different versions of stability and optimality.

* Stable Marriage on Networks. (Under Review)
We propose a solution for stable marriage problem on networks, where the male are incentivized to report their true preferences, and both the male and the female have incentives to invite others to enlarge the game.


Projects
------
* Mechanism Design for Matching on Social Networks
  * Project Purpose:
  * Main Work: We design mechanisms/algorithms for matching (including one-sided matching, e.g., Shapley Scarf housing market, and two-sided matching, e.g., stable marriage problem), with an extra focus on the social interaction of agents. In this new setting, traditional mechanisms (e.g., top trading cycles, deferred acceptance) fail to be incentive compatible, and the theoretical boundaries also change.

* Allocation Auto-Filter for Matching, Jun.2022-Sept.2022
  * Project purpose: build an auto-filter in Python to find desirable allocations for an arbitrary instance of one-sided matching or two-sided matching (especially matching over social networks); help find collar cases and provide insights for theoretical design. 
  * Main work: program stability, optimality, Incentive Compatibility, and other desired properties as constraints; program several commonly used network structures (for instance, small-world, ER graph, and GIRG) to run experiments and visualize the results.

* Incorporating Shapley Value into MARL Predator-Prey Game, Mar.2022-Jun.2022
  * Project purpose: design a heuristic Shapley-Q learning framework for semi-cooperative MARL games, represented by predator- prey; in predator-prey games, the predators cooperate to maximize global reward but also have extra strategies to increase / decrease their private reward / cost. 
  * Main work: use Shapley Value to decompose the reward function and make MARL more explainable; apply DQN-based neural networks to approximate Shapley Q-value; construct heuristic functions for the semi-cooperative model.

* Three WeChat Mini-program Products Development, Feb.2021-Nov.2023
  * Projects
    * Second-hand Good Trading Platform 
    * BookNet: Online Book Exchanging and Rating Community 
    * Smart School-Bus Management System for Kindergarten
  * Main work: model the business logic and separate them into function modules; lead the team to design and develop WeChat mini-programs (WeChat JavaScript for front-end, Python Flask for back-end, SQLite for database); follow up with on-site tests and help users get familiar with the program; support required maintenance and updates.
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Services
------
- Conference on Web and InterNet Economics (WINE 2023) Conference Preparation, Sept.2023-Dec.2023
- Python Programming Teaching Assistant (Professor Dengji Zhao), May.2023-Aug.2023
- Machine Learning Teaching Assistant (Professor Sibei Yang), Sept.2022-Jan.2023
- International Conference on Distributed AI (DAI 2021) Conference Preparation, Oct.2021-Jan.2022
- Algorithmic Game Theory MOOC Teaching Assistant (Professor Dengji Zhao), Sept.2021-Jan.2022
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->

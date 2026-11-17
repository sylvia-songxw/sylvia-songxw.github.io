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
* **Ph.D. in Computer Science and Technology**, a joint program of ShanghaiTech University and the Beijing Institute for General Artificial Intelligence (BIGAI), 2024.09–2027.06 (expected). Advisor: Prof. Dengji Zhao.
* **M.S. in Computer Science and Technology**, ShanghaiTech University, 2021.09–2024.06.
* **B.Eng. in Software Engineering**, a joint program of Beihang University and Beijing University of Technology, 2017.09–2021.06.

Research Interests
------
Autonomous decision-making and incentive design in multi-agent systems; reinforcement learning, game theory, and mechanism design; reputation, social norms, and emergent cooperation; continual learning and goal generation for LLM agents.

Publications
------
* **Stable Marriage on Networks** — Miao Li, Xinwei Song, Dengji Zhao. *AAMAS 2026*. [DOI](https://doi.org/10.65109/pkvj4128)
* **Designing Incentives for Networked Multi-agent Systems** — Xinwei Song. *AAAI 2026 Doctoral Consortium*. [DOI](https://doi.org/10.1609/aaai.v40i48.42167) · [PDF](https://ojs.aaai.org/index.php/AAAI/article/download/42167/46128)
* **Housing Market on Networks** — Xinwei Song, Tianyi Yang, Dengji Zhao. *AAMAS 2025*. [DOI](https://doi.org/10.65109/dvvr5292) · [arXiv](https://arxiv.org/abs/2303.09759)
* **Truthful and Stable One-sided Matching on Networks** — Tianyi Yang, Yuxiang Zhai, Dengji Zhao, Xinwei Song, Miao Li. *AAMAS 2024 (extended abstract)*. [DOI](https://doi.org/10.65109/pekx6502) · [arXiv](https://arxiv.org/abs/2201.05787)
* **Stable Marriages via Social Relationship** — Miao Li, Xinwei Song, Dengji Zhao. *DAI 2025*. [DOI](https://doi.org/10.1145/3772429.3772443)
* **Learning to Adapt through Reviews in Online Markets** — Xinwei Song et al. *WWW 2027, under review*.
* **Learning to Cooperate with Emergent Reputation via Multi-agent Reinforcement Learning** — Xinwei Song, Yizhe Huang, Dengji Zhao, Xue Feng. *AAAI 2027, under review*. [arXiv](https://arxiv.org/abs/2606.04359)
* **NormAct: Benchmarking Embodied Agents' Proactive Compliance with Unspoken Social Norms** — Shiyun Zhao, Xinwei Song, et al. *ARR October 2026, under review*. [arXiv](https://arxiv.org/abs/2606.27826)

Research Experience
------
### Reinforcement Learning for Multi-agent Decision Making (2024.09–present)
I study learning, adaptation, and behavior emergence in multi-agent systems, with an emphasis on information propagation, reputation, and social norms. Current work designs decentralized MARL methods that learn reputation systems end-to-end, and models online markets in which buyers learn how to purchase and review while sellers learn how to disclose information.

### Social Norm Compliance in Embodied Agents and Multimodal LLMs (2026.02–present)
I design social-norm compliance tasks on BIGAI's TongSim and validate them with human questionnaires, implement a NormBank-based RAG baseline, and analyze why retrieving implicit social norms is hard for multimodal planners. I also contribute to the main method: a norm hinter trained with supervised learning on model-generated norm-understanding data, which raises the norm-compliant task completion rate of existing agents.

### Matching Mechanism Design on Social Networks (2021.09–2025.06)
I formulate one-sided and two-sided matching on networks and characterize the theoretical bounds; design mechanisms that are incentive compatible in both preference and social-relationship reporting, stable, and optimal; and compare average satisfaction across mechanisms by simulation.

Teaching
------
* Teaching Assistant, Machine Learning, ShanghaiTech University (2022, 2025)
* Teaching Assistant, Python Programming (2023)
* Teaching Assistant, Algorithmic Game Theory MOOC (2021)

Academic Service
------
* Reviewer: AAMAS, NeurIPS, ICML; JAAMAS and IEEE TCSS (2024–present)
* Hotel and banquet organization: WINE 2023, DAI 2021
* Selected participant, 2026 Reinforcement Learning Summer School with Richard S. Sutton, Shanghai Innovation Institute

Skills
------
* **Programming & frameworks:** Python, Java, PyTorch, AI-assisted programming
* **LLM agents:** LLM/VLM agent evaluation, supervised fine-tuning, data construction, few-shot evaluation

Selected Projects
------
### Three WeChat Mini-programs (2021.09–2025.06, no longer being maintained)
Designed, developed, and operated three mini-programs: a kindergarten school-bus arrival notification app (about 200 users per semester over four semesters), BookNet, an online book exchange and rating community (about 30 participants per event), and a second-hand goods trading platform (about 80 participants per event). I modeled the business logic, split it into functional modules, led a small team (WeChat JavaScript front end, Python Flask back end, SQLite database), and supported on-site testing and maintenance.

### Shapley Value in a MARL Predator–Prey Game (2023.03–2023.06)
Designed a heuristic Shapley-Q learning framework for semi-cooperative MARL games in which predators cooperate for a global reward but also have private incentives. Used the Shapley value to decompose the reward function, DQN-based networks to approximate Shapley Q-values, and heuristic functions for the semi-cooperative model.

### Allocation Auto-filter for Matching (2022.06–2022.09)
Built a Python tool that searches for desirable allocations in arbitrary one-sided and two-sided matching instances, especially matching over social networks, to find corner cases and provide insights for theoretical design. Stability, optimality, and incentive compatibility are encoded as constraints, and several network structures (small-world, Erdős–Rényi, GIRG) are generated for experiments and visualization.

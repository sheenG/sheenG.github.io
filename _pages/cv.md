---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science,Beihang University (Supervised by **Prof. Wenfei Fan**), 2018 - now
  * GPA: 3.73 / 4.00, Ranking: 13/91 (Top 14%)
* B.S. in Information Management and Information Systems, Northwest A&F University, 2014 - 2018
  * Thesis : 基于顶点划分的并行图再分割算法研究
  * GPA: 3.8 / 4.00, Ranking: 1/318 (Top 1%)

Work experience
======
* Research Intern, Shenzhen Institute of Computing Sciences, Mar.2021 - Oct.2024)
  * Graph Pattern Mining
  * Recommendation Systems
  * Explainability

### Graph Data Mining and Recommendation System Optimization
**Project Overview**: RecLogic, a logic framework to enhance the accuracy of machine learning (ML) models for recommendation systems by integrating logic conditions to reduce false positives and false negatives without retraining models.

**Technical Approach**: (1) Developed prediction rules (TIEs) that integrate dual-star graph patterns with logic conditions, reducing false positives/negatives by 16.21% AUC in critical prediction zones (i.e., near the recommendation threshold). (2) Implemented a generation-based approach using LSTM for pattern generation and decision trees for predicate generation to learn TIEs. (3) Proposed a parallel algorithm for applying TIEs in the recommendation module, achieving scalable performance by parallelizing path matching.

**Tech Stack**: Python/PyTorch (traditional recommendation models), C++ (subgraph matching), LSTM, Decision Trees.

**Deployment**: SIGMOD 2023. Implemented in AIRec Recommendation platform. https://airec.grandhoo.com/

### Graph Neural Networks and Explainable Recommendation Systems
**Project Overview**:Makex, a logic approach to explaining why a GNN-based model M (𝑥, 𝑦) recommends item 𝑦 to user 𝑥，providing both global and local explanations for recommendations.

**Technical Approach**: (1) Proposed Rules for ExPlanations (REPs) defined by dual-star graph patterns and dependency, revealing the topological and feature conditions for recommendations. (2) Implemented a GNN-guided algorithm using Monte Carlo Tree Search (MCTS) to discover REPs and generate global explanations. (3) Utilized the 1-WL test to explain GNN behaviors, ensuring faithfulness to GNN predictions, achieving 32% higher recognizability and 42% higher reliability in global explanations compared to baselines. (4) Developed a Top-k algorithm for local explanations, the fidelity and sparsity of its top-1 explanation are 0.893 and 0.00225% on average, 80.62% and 3 orders of magnitude better than the baselines, respectively. It takes only 0.38s to generate top-1 explanation on large graphs, 75.8X faster than baselines on average.

**Tech Stack**: Python/PyTorch (GNNs), C++ (subgraph matching), MCTS, 1-WL test

**Deployment**: VLDB 2024. Implemented in MedHunter AI Drug Discovery Platform. https://medhunter.grandhoo.com/

### Graph Data Mining and Logic-Driven Sequential Recommendation
**Project Overview**: LDSRec, a novel framework that integrates logic rules with sequential recommendation models by representation learning to capture users' short-term behaviors and long-term preferences.

**Technical Approach**: (1) Defined SEquential Rules (SERs) that combine sequential graph patterns with logic preconditions, enabling polynomial-time representation learning. (2) Transformed user behavior sequences into a global heterogeneous graph, maintaining strict temporal order via path-centric subsequence division, and item co-occurrence dependencies, and capturing high-order dependencies through correlated interaction paths. (3) Combined SER-guided embeddings with original model outputs, optimized via contrastive learning to align logic rules with latent user interest representations. The model was further optimized using a loss function that integrates logic-driven contributions.

**Tech Stack**: Python/PyTorch (sequential recommendation), C++ (subgraph matching), LSTM/Transformer, contrastive learning

**Deployment**: Under submission VLDB 2025.



Honor
======
* Apr. 2024 ACM SIGMOD Student Support Scholarship Award
* Nov. 2021 Outstanding Student Cadre Award, Beihang University
* Oct. 2021 The First Prize Scholarship, Beihang University
* Jan. 2021 Outstanding Graduate Student Award, Beihang University
* Dec. 2020 President Scholarship for Graduate Students Award, Beihang University
* Nov. 2020 Outstanding Student Cadre Award, Beihang University
* Oct. 2020 The Second Prize Scholarship, Beihang University
* Oct. 2019 The Second Prize Scholarship, Beihang University
* Jun. 2018 Top 100 Outstanding Undergraduate Thesis Award, Northwest A&F University
* Nov. 2017 **National Scholarship**
* Nov. 2017 The First Prize Scholarship, Northwest A&F University
* Nov.2017 Outstanding Student, Northwest A&F University
* Nov. 2016 **National Scholarship**
* Nov. 2016 The First Prize Scholarship, Northwest A&F University
* Nov.2016 Outstanding Student, Northwest A&F University



Services
======
* Volunteer of VLDB 2024
* Sub-reviewer: TKDE 2023, EDBT 2023, ICDE 2024
* Teaching Assistant of Formal Languages and Automa, Beihang University, 2019

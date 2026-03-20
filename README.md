# MolPredictor
Robust ADMET property prediction via GINEConv and Evidential Deep Learning. Focusing on uncertainty quantification and GNN interpretability for drug discovery. 基于 GINEConv 与证据深度学习的鲁棒 ADMET 性质预测。专注于药物研发中的不确定性量化与图神经网络可解释性研究。)

# MolPredictor: Robust ADMET Property Prediction

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Red Hat Certified](https://img.shields.io/badge/Red%20Hat-Certified%20(RHCSA)-red?logo=red-hat)](https://www.redhat.com/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:vincentarthurleung@gmail.com)

##  Overview / 项目概述
**MolPredictor** aims to solve two critical bottlenecks in Graph Neural Networks (GNNs) for **ADMET** (Absorption, Distribution, Metabolism, Excretion, and Toxicity) prediction: unreliable predictions caused by **Out-of-Distribution (OOD)** data and the "black-box" nature of model decision-making.

By integrating **Evidential Deep Learning (EDL)** for uncertainty quantification and **GNNExplainer** for pharmacophore extraction, this project enhances the reliability and interpretability of AI-driven drug discovery in real-world biochemical scenarios.

(Chinese translation)
**MolPredictor** 致力于解决药物研发早期阶段 GNN 模型在 **ADMET**（吸收、分布、代谢、排泄、毒性）性质预测中的两大痛点：**数据分布偏移 (OOD)** 导致的预测不可靠，以及模型决策的“黑盒”属性。本项目通过引入 **证据深度学习 (EDL)** 实现不确定性量化，并结合 **GNNExplainer** 提取关键药效团，提升模型在真实生化实验场景下的可靠性与可解释性。

-----------------------------

##   Key Features / 核心特性
* **Robust Graph Backbone**: Built with **GINEConv** to capture both node (atom) and edge (bond) features of molecular graphs.
    * **鲁棒图主干**: 基于 **GINEConv** 构建，能够同时提取分子图的节点（原子）与边缘（化学键）特征。
* **Uncertainty Quantification**: Implements EDL and MC Dropout to identify epistemic uncertainty and filter OOD samples.
    * **不确定性量化**: 集成证据深度学习与蒙特卡洛采样，识别认知不确定性，有效过滤分布外（OOD）样本。
* **Explainable AI (XAI)**: Utilizes Graph Masking to locate key subgraphs (pharmacophores) and validate them against pharmacological knowledge.
    * **可解释性 AI**: 利用图遮掩技术定位决定药效的关键子图（药效团），并与经典药理学知识进行比对验证。
* **Enterprise-Grade Engineering**: Standardized **Docker** deployment and high-performance training pipelines following Red Hat (RHCSA) standards.
    * **工业级工程标准**: 采用 **Docker** 容器化部署，遵循红帽（RHCSA）标准的标准化训练流水线。

---

## 📅 Roadmap / 项目路线图
- [x] **Phase 1: GNN Baseline (Q1 2026)**
    - Integration of MoleculeNet (Tox21, BBBP) datasets.
    - [x] 分子数据集集成与基础模型搭建。
- [ ] **Phase 2: Uncertainty Modeling (Q2 2026)**
    - Implementation of the EDL framework for robust reliability.
    - [ ] 实现证据深度学习框架，提升模型鲁棒性。
- [ ] **Phase 3: Explainability & Publication (Q3 2026)**
    - Pharmacophore visualization and submission to **JCIM/Bioinformatics**.
    - [ ] 药效团可视化，冲击 **JCIM/Bioinformatics** 等学术期刊。

---

## 🛠️ Tech Stack / 技术栈
* **Deep Learning**: PyTorch, PyTorch Geometric
* **Cheminformatics**: RDKit
* **Infrastructure**: Linux (Ubuntu/WSL2), Docker, RHCSA-level System Admin
* **Environment**: Conda / Docker Containerization

---

## 📜 Academic Goals / 学术目标
This project is part of a long-term research plan for **AI for Science (AI4S)**. We aim to contribute high-quality, reproducible code to the community and secure full-funded PhD opportunities in top-tier institutions (e.g., U.S. Top 30).

本项目是 **AI for Science (AI4S)** 长期研究计划的一部分。我们旨在为社区贡献高质量、可复现的开源代码，并以此支撑冲击全球顶尖院校（如美国 Top 30）的直博申请。

---
**Contact:
    ** Name ** [Vincent Arthur Leung 梁振雄] 
    ** Email ** 
        ** Academic ** [20251008460@stu.shzu.edu.cn]
        ** Personal ** [vincentarthurleung@gmail.com]
**Location:** Shihezi University / CAS Institute of Automation (Collaboration)

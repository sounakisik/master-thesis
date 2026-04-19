# Master Thesis: Oversampling Methods for Imbalanced Classification in Graph-Structured Data

## Overview
This repository contains the work related to my master's thesis on handling **class imbalance in classification problems**, with a focus on both **classical oversampling methods** and **graph-based oversampling techniques**.

The study begins with traditional methods such as:
- SMOTE
- K-Means SMOTE
- Borderline-SMOTE

and then extends the discussion to **graph-structured datasets**, where node relationships and graph topology play an important role in learning. In this setting, the thesis explores advanced graph oversampling methods such as:
- GraphSMOTE
- GTS
- FG-SMOTE
- ESA-GCN

The objective is to understand how oversampling strategies can improve predictive performance and fairness in imbalanced node classification tasks.

---

## Abstract
Class imbalance poses significant challenges in classification tasks, often leading to poor predictive performance for minority classes. This project initially focused on classical oversampling strategies, particularly SMOTE and its improved variants such as k-means SMOTE and Borderline SMOTE. These methods aim to balance class distributions by generating synthetic data in safe or informative regions of the feature space. While effective for tabular data, their limitations become apparent when extended to graph-structured datasets, where node relationships and topology are crucial for learning.

To address this, the study extends the SMOTE framework to graphs by exploring GraphSMOTE and its advanced variants—GTS, FG-SMOTE, and ESA-GCN. These methods introduce structure-aware interpolation, edge generation, fairness-aware sampling, and robustness to noise through attention mechanisms. Comprehensive experiments on real-world graph datasets, including Cora, PubMed, YelpChi, and Credit, demonstrate improvements in both classification accuracy and fairness. The project concludes that graph-specific oversampling strategies, when thoughtfully designed, can significantly enhance performance and equity in node classification tasks.

---

## Key Objectives
- Study the impact of **class imbalance** on classification performance
- Understand the working of **traditional oversampling methods**
- Analyze why classical oversampling is insufficient for **graph data**
- Explore **graph-aware oversampling frameworks**
- Evaluate their effect on **accuracy**, **minority-class performance**, and **fairness**

---

## Methods Covered

### Classical Oversampling Methods
- **SMOTE**
- **K-Means SMOTE**
- **Borderline-SMOTE**

### Graph-Based Methods
- **GraphSMOTE**
- **GTS**
- **FG-SMOTE**
- **ESA-GCN**

---

## Datasets
The experiments and discussion in this thesis involve benchmark graph datasets such as:
- **Cora**
- **PubMed**
- **YelpChi**
- **Credit**

---

## Repository Structure
```text
.
├── thesis.pdf              # Final thesis document
├── README.md               # Project overview
├── data/                   # Dataset files or dataset instructions
├── notebooks/              # Jupyter notebooks for experiments/analysis
├── src/                    # Source code
├── results/                # Output plots, tables, and evaluation results
└── references/             # Related papers / notes

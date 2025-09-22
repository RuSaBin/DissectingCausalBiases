# Dissecting Causal Biases

[![arXiv](https://img.shields.io/badge/arXiv-2310.13364-b31b1b.svg)](https://arxiv.org/abs/2310.13364)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This repository contains the **code and data** accompanying the paper:

> **Dissecting Causal Biases**  
> *Rūta Binkytė, Sami Zhioua, Yassine Turki*  
> arXiv: [2310.13364](https://arxiv.org/abs/2310.13364)

---

## 📄 Abstract (from the paper)

Accurately measuring discrimination in machine learning–based automated decision systems is required to address the vital issue of fairness between subpopulations and/or individuals. Any bias in measuring discrimination can lead to either amplification or underestimation of the true value of discrimination. This paper focuses on a class of bias originating in the way training data is generated and/or collected. We call such class **causal biases** and use tools from the field of causality to formally define and analyze them.  
Four sources of bias are considered: **confounding, selection, measurement, and interaction**.  
The main contribution of this paper is to provide, for each source of bias, a closed-form expression in terms of the model parameters. This makes it possible to analyze the behavior of each source of bias, in particular, in which cases they are absent and in which other cases they are maximized.

---

## ⚙️ Installation & Setup

### Requirements
- Python 3.8+


🙏 Citation

If you use this repository or its content, please cite:

@article{BinkyteZhiouaTurki2023,
  title   = {Dissecting Causal Biases},
  author  = {Rūta Binkytė and Sami Zhioua and Yassine Turki},
  year    = {2023},
  eprint  = {2310.13364},
  archivePrefix = {arXiv},
  primaryClass   = {cs.LG}
}

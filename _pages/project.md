---
title: "Projects"
permalink: /projects/
author_profile: true
---

---
## Development of Potential-free Data-driven Molecular Dynamics (PDMD) for Variable-sized Water Clusters (H<sub>2</sub>O)<sub>n ≤ 21</sub>
- PDMD utilizes Smooth Overlap of Atomic Positions descripor to generate high-dimensional features, which satisfy equivariance, and leverages ChemGNN, a graph neural network-based model that satisfactorily capture the characteristics of atoms' local chemical environment and greatly enhance the learning ability of complex molecular structures, to predict both system energy and atomic forces
- By an iterative self-consistent approach, a converged PDMD is obtained, which outperforms the state-of-the-art DeepMD by 83% in terms of energy MAE and 201% for force prediction.
- PDMD achieves outstanding performance on the (H<sub>2</sub>O)<sub>n ≤ 21</sub> dataset, which has both gas and gas-liquid phase transition features, providing a diverse set of chemical environments. This highlights its cross-phase predictive power, delivering ultra-fast, general-purpose MD simulations while retaining ab initio accuracy.

![image](https://github.com/01Yan/hyyan.github.io/tree/master/images/model_structure.jpg)

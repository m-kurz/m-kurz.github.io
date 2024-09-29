---
title: Toward discretization-consistent closure schemes for large eddy simulation
  using reinforcement learning
authors:
- Andrea Beck
- marius
date: '2023-12-12'
publishDate: '2024-09-11T19:45:20.280781Z'
publication_types:
- article-journal
publication: '*Physics of Fluids*'
doi: 10.1063/5.0176223
abstract: This study proposes a novel method for developing discretization-consistent closure schemes for implicitly filtered large eddy simulation (LES). Here, the induced filter kernel and, thus, the closure terms are determined by the properties of the grid and the discretization operator, leading to additional computational subgrid terms that are generally unknown in a priori analysis. In this work, the task of adapting the coefficients of LES closure models is thus framed as a Markov decision process and solved in an a posteriori manner with reinforcement learning (RL). This optimization framework is applied to both explicit and implicit closure models. The explicit model is based on an element-local eddy viscosity model. The optimized model is found to adapt its induced viscosity within discontinuous Galerkin (DG) methods to homogenize the dissipation within an element by adding more viscosity near its center. For the implicit modeling, RL is applied to identify an optimal blending strategy for a hybrid DG and finite volume (FV) scheme. The resulting optimized discretization yields more accurate results in LES than either the pure DG or FV method and renders itself as a viable modeling ansatz that could initiate a novel class of high-order schemes for compressible turbulence by combining turbulence modeling with shock capturing in a single framework. All newly derived models achieve accurate results that either match or outperform traditional models for different discretizations and resolutions. Overall, the results demonstrate that the proposed RL optimization can provide discretization-consistent closures that could reduce the uncertainty in implicitly filtered LES.
links:
- name: URL
  url: https://doi.org/10.1063/5.0176223
featured: true
summary: This study proposes a novel method for developing discretization-consistent closure schemes for implicitly filtered large eddy simulation using reinforcement learning.
tags:
- Deep Reinforcement Learning
- Large Eddy Simulation
- Turbulence Modeling
---

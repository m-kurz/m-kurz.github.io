---
title: Machine Learning Methods for Modeling Turbulence in Large Eddy Simulations
authors:
- marius
date: '2024-01-01'
publishDate: '2024-09-11T19:45:20.248500Z'
publication_types:
- book
publication: '*Verlag Dr. Hut*'
abstract: The reliable prediction of turbulent flows is of crucial importance since
  turbulence is prevalent in the majority of flows found in science and engineering.
  Turbulence is a multi-scale phenomenon, for which flow features can span several
  orders of magnitude in size. This results in enormous resolution requirements in
  numerical simulations of turbulent flow. The framework of large eddy simulation
  relaxes these resolution demands by resolving only the largest, most energetic features
  of the flow and approximating the dynamics of the smaller, unresolved scales with
  turbulence models. The goal of this thesis is to leverage the recent advances in
  machine learning methods to formulate data-driven modeling strategies for implicitly
  filtered large eddy simulation. To this end, two modeling strategies are devised
  based on the supervised and the reinforcement learning paradigms. First, artificial
  neural networks are trained using supervised learning to recover the unknown closure
  terms from the filtered flow field. It is demonstrated that recurrent neural networks
  can predict the unknown closure terms with excellent accuracy. The second modeling
  strategy is based on the reinforcement learning paradigm. For this, Relexi is introduced
  as a novel reinforcement learning framework that allows to employ legacy flow solvers
  as training environments at scale. With Relexi, artificial neural networks are trained
  within forced homogeneous isotropic turbulence to adapt the parameters of traditional
  turbulence models dynamically in space and time. The trained models provide accurate
  and stable simulations and generalize well to other resolutions and higher Reynolds
  numbers. It is demonstrated within this thesis that machine learning methods can
  be applied to derive data-driven turbulence models for implicitly filtered large
  eddy simulation and that these models can be trained and incorporated efficiently
  into practical simulations on high-performance computing systems
---

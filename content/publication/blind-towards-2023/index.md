---
title: Towards Exascale CFD Simulations Using the Discontinuous Galerkin Solver FLEXI
authors:
- Marcel Blind
- Min Gao
- Daniel Kempf
- Patrick Kopper
- Marius Kurz
- Anna Schwarz
- Andrea Beck
date: '2023-06-01'
publishDate: '2024-09-11T19:45:20.312152Z'
publication_types:
- manuscript
publication: '*arXiv*'
abstract: Modern high-order discretizations bear considerable potential for the exascale
  era due to their high fidelity and the high, local computational load that allows
  for computational efficiency in massively parallel simulations. To this end, the
  discontinuous Galerkin (DG) framework FLEXI was selected to demonstrate exascale
  readiness within the Center of Excellence for Exascale CFD (CEEC) by simulating
  shock buffet on a three-dimensional wing segment at transsonic flight conditions.
  This paper summarizes the recent progress made to enable the simulation of this
  challenging exascale problem. For this, it is first demonstrated that FLEXI scales
  excellently to over 500 000 CPU cores on HAWK at the HLRS. To tackle the considerable
  resolution requirements near the wall, a novel wall model is proposed that takes
  compressibility effects into account and yields decent results for the simulation
  of a NACA 64A-110 airfoil. To address the shocks in the domain, a finite-volume-based
  shock capturing method was implemented in FLEXI, which is validated here using the
  simulation of a linear compressor cascade at supersonic flow conditions, where the
  method is demonstrated to yield efficient, robust and accurate results. Lastly,
  we present the TensorFlow-Fortran-Binding (TFFB) as an easy-to-use library to deploy
  trained machine learning models in Fortran solvers such as FLEXI.
tags:
- Computer Science - Distributed
- Parallel
- and Cluster Computing
- own
links:
- name: URL
  url: http://arxiv.org/abs/2306.12891
---

---
title: 'GALAEXI: Solving complex compressible flows with high-order discontinuous
  Galerkin methods on accelerator-based systems'
authors:
- Daniel Kempf
- marius
- Marcel Blind
- Patrick Kopper
- Philipp Offenhäuser
- Anna Schwarz
- Spencer Starr
- Jens Keim
- Andrea Beck
author_notes:
- Author
date: '2024-04-01'
publishDate: '2024-09-11T19:45:20.232582Z'
publication_types:
- manuscript
publication: '*arXiv*'
doi: 10.48550/arXiv.2404.12703
abstract: This work presents GALAEXI as a novel, energy-efficient flow solver for
  the simulation of compressible flows on unstructured meshes leveraging the parallel
  computing power of modern Graphics Processing Units (GPUs). GALAEXI implements the
  high-order Discontinuous Galerkin Spectral Element Method (DGSEM) using shock capturing
  with a finite-volume subcell approach to ensure the stability of the high-order
  scheme near shocks. This work provides details on the general code design, the parallelization
  strategy, and the implementation approach for the compute kernels with a focus on
  the element local mappings between volume and surface data due to the unstructured
  mesh. GALAEXI exhibits excellent strong scaling properties up to 1024 GPUs if each
  GPU is assigned a minimum of one million degrees of freedom degrees of freedom.
  To verify its implementation, a convergence study is performed that recovers the
  theoretical order of convergence of the implemented numerical schemes. Moreover,
  the solver is validated using both the incompressible and compressible formulation
  of the Taylor-Green-Vortex at a Mach number of 0.1 and 1.25, respectively. A mesh
  convergence study shows that the results converge to the high-fidelity reference
  solution and that the results match the original CPU implementation. Finally, GALAEXI
  is applied to a large-scale wall-resolved large eddy simulation of a linear cascade
  of the NASA Rotor 37. Here, the supersonic region and shocks at the leading edge
  are captured accurately and robustly by the implemented shock-capturing approach.
  It is demonstrated that GALAEXI requires less than half of the energy to carry out
  this simulation in comparison to the reference CPU implementation. This renders
  GALAEXI as a potent tool for accurate and efficient simulations of compressible
  flows in the realm of exascale computing and the associated new HPC architectures.
tags:
- Computer Science - Mathematical Software
- Computer Science - Computational Engineering
- Finance
- and Science
links:
- name: URL
  url: http://arxiv.org/abs/2404.12703
---

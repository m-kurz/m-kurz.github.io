---
title: An efficient sliding mesh interface method for high-order discontinuous Galerkin
  schemes
authors:
- Jakob Dürrwächter
- marius
- Patrick Kopper
- Daniel Kempf
- Claus-Dieter Munz
- Andrea Beck
date: '2021-03-15'
publishDate: '2024-09-11T19:45:20.291175Z'
publication_types:
- article-journal
publication: '*Computers & Fluids*'
doi: 10.1016/j.compfluid.2020.104825
abstract: Sliding meshes are a powerful method to treat deformed domains in computational fluid dynamics, where different parts of the domain are in relative motion. In this paper, we present an efficient implementation of a sliding mesh method into a discontinuous Galerkin compressible Navier-Stokes solver and its application to a large eddy simulation of a 1-1/2 stage turbine. The method is based on the mortar method and is high-order accurate. It can handle three-dimensional sliding mesh interfaces with various interface shapes. For plane interfaces, which are the most common case, conservativity and free-stream preservation are ensured. We put an emphasis on efficient parallel implementation. Our implementation generates little computational and storage overhead. Inter-node communication via MPI in a dynamically changing mesh topology is reduced to a bare minimum by ensuring a priori information about communication partners and data sorting. We provide performance and scaling results showing the capability of the implementation strategy. Apart from analytical validation computations and convergence results, we present a wall-resolved implicit LES of the 1-1/2 stage Aachen turbine test case as a large scale practical application example.
links:
- name: URL
  url: https://linkinghub.elsevier.com/retrieve/pii/S0045793020303959
featured: true
tags:
- High-Performance Computing
- Large Eddy Simulation
- High-Order Numerical Methods
summary: This work proposes an efficient sliding mesh method for discontinuous Galerkin schemes. The method is applied to a large-scale, time-resolved large eddy simulation of a 1-1/2 stage turbine.
---

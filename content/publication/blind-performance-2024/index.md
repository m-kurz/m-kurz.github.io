---
title: Performance Improvements for Large-Scale Simulations using the Discontinuous
  Galerkin Framework FLEXI
authors:
- Marcel Blind
- Patrick Kopper
- Daniel Kempf
- Marius Kurz
- Anna Schwarz
- Claus-Dieter Munz
- Andrea Beck
date: '2024-01-01'
publishDate: '2024-09-11T19:45:20.259912Z'
publication_types:
- paper-conference
publication: "*High Performance Computing in Science and Engineering '22*"
doi: 10.1007/978-3-031-46870-4_17
abstract: Large-scale simulations pose significant challenges not only to the solver
  itself but also to the pre- and postprocessing framework. Hence, we present generally
  applicable improvements to enhance the performance of those tools and thus increase
  the feasibility of large-scale jobs and convergence studies. To accomplish this,
  we use a shared memory approach implemented in the Message Passing Interface (MPI)
  libraries. Additionally, we improve the read and write performance of the flow solver
  during runtime to minimize the load imposed on the file system. A detailed discussion
  of the current performance and scaling behavior is given for up to 262144 processes.
  FLEXI shows excellent scalability for all tested features. We conclude by showing
  selected applications, where we use the introduced improvements to maximize performance.
---

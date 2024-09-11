---
title: Development of turbulent inflow methods for the high order HPC framework FLEXI
authors:
- Daniel Kempf
- Min Gao
- Andrea Beck
- Marcel Blind
- Patrick Kopper
- Thomas Kuhn
- marius
- Anna Schwarz
- Claus-Dieter Munz
date: '2023-01-01'
publishDate: '2024-09-11T19:45:20.269618Z'
publication_types:
- paper-conference
publication: "*High Performance Computing in Science and Engineering '21*"
doi: 10.1007/978-3-031-17937-2_17
abstract: Turbulent inflow methods offer new possibilities for an efficient simulation
  by reducing the computational domain to the interesting parts. Typical examples
  are turbulent flow over cavities, around obstacles or in the context of zonal large
  eddy simulations. Within this work, we present the current state of two turbulent
  inflow methods implemented in our high order discontinuous Galerkin code FLEXI with
  special focus laid on HPC applications. We present the recycling-rescaling anisotropic
  linear forcing (RRALF), a combination of a modified recycling-rescaling approach
  and an anisotropic linear forcing, and a synthetic eddy method (SEM). For both methods,
  the simulation of a turbulent boundary layer along a flat plate is used as validation
  case. For the RRALF method, a zonal large eddy simulation of the rear part of a
  tripped subsonic turbulent boundary layer over a flat plate is presented. The SEM
  is validated in the case of a supersonic turbulent boundary layer using data from
  literature at the inflow. In the course of the cluster upgrade to the HPE Apollo
  system at HLRS, our framework was examined for performance on the new hardware architecture.
  Optimizations and adaptations were carried out, for which we will present current
  performance data.
tags:
- High-Performance Computing
- Large Eddy Simulation
---

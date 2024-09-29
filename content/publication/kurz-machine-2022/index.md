---
title: A machine learning framework for LES closure terms
authors:
- marius
- Andrea Beck
date: '2022-01-10'
publishDate: '2024-09-11T19:45:20.301453Z'
publication_types:
- article-journal
publication: '*Electronic Transactions on Numerical Analysis*'
doi: 10.1553/etna_vol56s117
abstract: In the present work, we explore the capability of artificial neural networks (ANN) to predict the closure terms for large eddy simulations (LES) solely from coarse-scale data. To this end, we derive a consistent framework for LES closure models, with special emphasis laid upon the incorporation of implicit discretization-based filters and numerical approximation errors. We investigate implicit filter types that are inspired by the solution representation of discontinuous Galerkin and finite volume schemes and mimic the behavior of the discretization operator, and a global Fourier cutoff filter as a representative of a typical explicit LES filter. Within the perfect LES framework, we compute the exact closure terms for the different LES filter functions from direct numerical simulation results of decaying homogeneous isotropic turbulence. Multiple ANN with a multilayer perceptron (MLP) or a gated recurrent unit (GRU) architecture are trained to predict the computed closure terms solely from coarse-scale input data. For the given application, the GRU architecture clearly outperforms the MLP networks in terms of accuracy, whilst reaching up to 99.9% correlation between the networks’ predictions and the exact closure terms for all considered filter functions. The GRU networks are also shown to generalize well across different LES filters and resolutions. The present study can thus be seen as a starting point for the investigation of data-based modeling approaches for LES, which not only include the physical closure terms, but account for the discretization effects in implicitly filtered LES as well.
links:
- name: URL
  url: 
    https://etna.ricam.oeaw.ac.at/volumes/2021-2030/vol56/abstract.php?vol=56&pages=117-137
---

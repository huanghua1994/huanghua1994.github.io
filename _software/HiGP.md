---
title: "HiGP: High-Performance Python Package for Gaussian Process"
collection: software
excerpt: "HiGP is a high-performance Python package for Gaussian Process."
---

Gaussian processes (GPs) are a set of flexible, non-parametric Bayesian methods for modeling complex data. [HiGP](https://github.com/huanghua1994/HiGP) is a high-performance Python package for GP regression (GPR) and GP classification (GPC). HiGP uses multiple new algorithms and techniques to accelerate GP model training and inference for any size of data sets:

* Highly-optimized C++ implementations of computation kernels, including kernel matrix evaluation, Krylov subspace solvers, preconditioner, and gradient calculations.
* The Adaptive Factorized Nystrom preconditioner for efficient and robust gradient calculations.
* $\mathcal{H}^2$ matrix algorithms from the H2Pack library for efficient handling of 2D/3D spatial data.
* On-the-fly running mode for handling large size datasets without using a lot of memory.
* Works with PyTorch optimizer -- you can use HiGP in your PyTorch-based data science workflow easily!

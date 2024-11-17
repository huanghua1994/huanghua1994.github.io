---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* Ph.D. in Computational Science and Engineering, Georgia Institute of Technology, 2019.5 - 2024.8 (expected), advisor: [Prof. Edmond Chow](https://www.cc.gatech.edu/~echow/).
* M.S. in Computer Science, Georgia Institute of Technology, 2017.8 - 2019.5, advisor: [Prof. Edmond Chow](https://www.cc.gatech.edu/~echow/).
* B.S. in Information and Computing Science, Sun Yat-sen University, 2013.8 - 2017.6, advisor: Dr. Weicai Ye（叶纬材博士）.

## Skills

* Programming languages: C, C++, MATLAB, Fortran, Python
* Frameworks and technologies: OpenMP, MPI, CUDA, OpenCL, SYCL, x86 intrinsics, ARM (NEON and SVE) intrinsics

## Work Experience

* Developer Technology Engineer, NVIDIA (2024.08 - now)

## Intern Experience

* Software Engineer Intern, Meta (Facebook) Inc (2021.5 - 2021.8, supervisor: Dr. [Xing Liu](https://scholar.google.com/citations?user=ewRsKt4AAAAJ&hl=en))
  * Investigated different parallelization schemes of the Mixture of Experts (MoE) model.
  * Implemented a PyTorch-based hybrid parallel MoE model for a recommendation system.
  * Delivered a 6x speedup on 64 NVIDIA V100 GPUs compared to the existing MoE model deployed in production.
* Research Intern, Intel Corporation (2020.8 - 2020.12, supervisor: Dr. [Jeff Hammond](https://jeffhammond.github.io/))
  * Analyzed the code of Kokkos Remote Workspace and NVSHMEM.
  * Designed and implemented CL-PGAS using SYCL + MPI-3, the first library in the industry enabling inter-node data transfer controlled by kernels running on Intel / NVIDIA / AMD GPUs.
  * Achieved a 95 % performance level compared to NVIDIA’s proprietary library NVSHMEM.

## Research Experience

* Graduate Research Assistant, Georgia Institute of Technology (2018.1 - 2024.8, supervisor: Prof. [Edmond Chow](https://faculty.cc.gatech.edu/~echow/))
  * Accelerating quantum chemistry calculations: up to 6x overall speedup of Hartree-Fock calculation for a 1208-atom molecular system with multiple optimizations.
  * Developing the H2Pack library: up to 6x speedup over state-of-the-art FMM-based method in high-accuracy calculations, 90% memory usage reduction and a 7x speedup compared to contemporary methods for  quantum chemistry and hydrodynamic simulation calculations.
  * Designing parallel linear algebra algorithms: up to 25% and 4x speedup for dense / sparse matrix multiplications compared to state-of-the-art method.

## Publications

### Peer-reviewed Conference Publications

[C.4] <span style="color:blue">**[SC 24]**</span> *Many-Body Electronic Correlation Energy using Krylov Subspace Linear Solvers*.  
[Shikhar Shah](https://orcid.org/0000-0002-7943-8907), [Boqin Zhang](https://scholar.google.com/citations?user=9YpTGugAAAAJ&hl=en), **Hua Huang**, [John E. Pask](https://people.llnl.gov/pask1), [Phanish Suryanarayana](https://ce.gatech.edu/directory/person/phanish-suryanarayana), and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
International Conference for High Performance Computing, Networking, Storage, and Analysis (SC), 2024.  
[pdf](https://huanghua1994.github.io/files/SC24-SPARC-RPA.pdf){: .btn} [IEEE](https://www.computer.org/csdl/proceedings-article/sc/2024/529100a946/21HUW7F4gI8){: .btn}

[C.3]  <span style="color:blue">**[SC 22]**</span> *CA3DMM: A New Algorithm Based on a Unified View of Parallel Matrix Multiplication*.  
**Hua Huang** and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
International Conference for High Performance Computing, Networking, Storage, and Analysis (SC), 2022.  
[pdf](https://huanghua1994.github.io/files/SC22-Huang-Chow.pdf){: .btn} [ACM (includes presentation video)](https://dl.acm.org/doi/abs/10.5555/3571885.3571922){: .btn}

[C.2]  <span style="color:blue">**[IPDPS 19]**</span> *Overlapping Communications with Other Communications and its Application to Distributed Dense Matrix Computations*.
**Hua Huang** and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
International Parallel & Distributed Processing Symposium (IPDPS), 2019.  
[pdf](huanghua1994.github.io/files/IPDPS19-Huang-Chow.pdf){: .btn} [IEEE](https://ieeexplore.ieee.org/abstract/document/8821006){: .btn}

[C.1]  <span style="color:blue">**[SC 18]**</span> *Accelerating Quantum Chemistry with Vectorized and Batched Integrals*.  
**Hua Huang** and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
International Conference for High Performance Computing, Networking, Storage, and Analysis (SC), 2018.  
[pdf](https://huanghua1994.github.io/files/SC18-Huang-Chow.pdf){: .btn} [ACM](https://dl.acm.org/doi/10.5555/3291656.3291711){: .btn}

### Peer-reviewed Journal Publications

[J.9] <span style="color:blue">**[IEEE Trans. Parallel Distrib. Syst]**</span> *Exploring the Design Space of Distributed Parallel Sparse Matrix‑Multiple Vector Multiplication*.
**Hua Huang** and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
IEEE Transactions on Parallel and Distributed Systems, 35(11), 1977-1988 (2024).  
[pdf](https://huanghua1994.github.io/files/TPDS-CRP-SpMM.pdf){: .btn} [IEEE](https://ieeexplore.ieee.org/abstract/document/10660551){: .btn}

[J.8] <span style="color:blue">**[SIAM J. Sci. Comput.]**</span> *An Adaptive Factorized Nystrom Preconditioner for Kernel Matrices*.
[Shifan Zhao](https://matherheart.github.io/), [Tianshi Xu](https://math.emory.edu/~txu41/), **Hua Huang**, [Edmond Chow](https://faculty.cc.gatech.edu/~echow/), and [Yuanzhe Xi](http://www.math.emory.edu/~yxi26/index.html).  
SIAM Journal on Scientific Computing, 46(4), A2351-A2376 (2024).  
[pdf](https://huanghua1994.github.io/files/SISC-AFN.pdf){: .btn} [SIAM](https://epubs.siam.org/doi/10.1137/23M1565139){: .btn}

[J.7]  <span style="color:blue">**[SIAM J. Sci. Comput.]**</span> *Data-Driven Construction of Hierarchical Matrices with Nested Bases*.  
[Difeng Cai](https://www.smu.edu/Dedman/Academics/Departments/Math/People/Faculty/DifengCai), **Hua Huang**, [Edmond Chow](https://faculty.cc.gatech.edu/~echow/), and [Yuanzhe Xi](http://www.math.emory.edu/~yxi26/index.html).  
SIAM Journal on Scientific Computing, 46(2), S24-S50 (2024).  
[pdf](https://huanghua1994.github.io/files/SIMAX-HiDR.pdf){: .btn} [SIAM](https://epubs.siam.org/doi/full/10.1137/22M1500848){: .btn}

[J.6]  <span style="color:blue">**[J. Comput. Phys.]**</span> *A Hierarchical Matrix Approach for Computing Hydrodynamic Interactions*.  
[Xin Xing](https://scholar.google.com/citations?hl=en&user=NBdb9XoAAAAJ&view_op=list_works&sortby=pubdate), **Hua Huang**, and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
Journal of Computational Physics, 448, 110761 (2022).  
[pdf](https://huanghua1994.github.io/files/JCP-H2RPY-Xing-Huang-Chow.pdf){: .btn} [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0021999121006562){: .btn}

[J.5]  <span style="color:blue">**[SoftwareX]**</span> *SPARC: Simulation Package for Ab-initio Real-space Calculations*.  
[Qimen Xu](https://scholar.google.com/citations?hl=en&user=V6tGLpoAAAAJ&view_op=list_works&sortby=pubdate), [Abhiraj Sharma](https://scholar.google.com/citations?hl=en&user=IiQqaEwAAAAJ&view_op=list_works&sortby=pubdate),  [Benjamin Comer](https://scholar.google.com/citations?hl=en&user=3pZTa4wAAAAJ&view_op=list_works&sortby=pubdate), **Hua Huang**, [Edmond Chow](https://faculty.cc.gatech.edu/~echow/), [Andrew J Medford](https://www.chbe.gatech.edu/people/andrew-j-medford), [John E Pask](https://people.llnl.gov/pask1), and [Phanish Suryanarayana](https://ce.gatech.edu/directory/person/phanish-suryanarayana).
SoftwareX, 15, 100709 (2021).  
[pdf](https://huanghua1994.github.io/files/SoftwareX-SPARC.pdf){: .btn} [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2352711021000546){: .btn}

[J.4]  <span style="color:blue">**[SIAM J. Matrix Anal. Appl.]**</span> *Efficient Construction of an HSS Preconditioner for Symmetric Positive Definite H2 Matrices*.  
[Xin Xing](https://scholar.google.com/citations?hl=en&user=NBdb9XoAAAAJ&view_op=list_works&sortby=pubdate), **Hua Huang**, and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
SIAM Journal on Matrix Analysis and Applications, 42(2), 683–707 (2021).  
[pdf](https://huanghua1994.github.io/files/SIMAX-SPDHSS-Xing-Huang-Chow.pdf){: .btn} [SIAM](https://epubs.siam.org/doi/abs/10.1137/20M1365776){: .btn}

[J.3]  <span style="color:blue">**[ACM Trans. Math. Softw]**</span> *H2Pack: High-Performance H2 Matrix Package for Kernel Matrices Using the Proxy Point Method*.  
**Hua Huang**, [Xin Xing](https://scholar.google.com/citations?hl=en&user=NBdb9XoAAAAJ&view_op=list_works&sortby=pubdate), and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
ACM Transactions on Mathematical Software, 47(1), 1-29 (2020).  
[pdf](https://huanghua1994.github.io/files/ACMTOMS-H2Pack-Huang-Xing-Chow.pdf){: .btn} [ACM](https://dl.acm.org/doi/abs/10.1145/3412850){: .btn}

[J.2]  <span style="color:blue">**[J. Chem. Phys.]**</span> *A Linear Scaling Hierarchical Block Low-rank Representation of the Electron Repulsion Integral Tensor*.  
[Xin Xing](https://scholar.google.com/citations?hl=en&user=NBdb9XoAAAAJ&view_op=list_works&sortby=pubdate), **Hua Huang**, and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
Journal of Chemical Physics, 153, 084119 (2020).  
[pdf](https://huanghua1994.github.io/files/JCP-H2ERI-Xing-Huang-Chow.pdf){: .btn} [AIP](https://pubs.aip.org/aip/jcp/article/153/8/084119/1061798/A-linear-scaling-hierarchical-block-low-rank){: .btn}

[J.1]  <span style="color:blue">**[J. Chem. Phys.]**</span> *Techniques for High-Performance Construction of Fock Matrices*.  
**Hua Huang**, [David Sherrill](https://chemistry.gatech.edu/people/david-sherrill), and [Edmond Chow](https://faculty.cc.gatech.edu/~echow/).  
Journal of Chemical Physics, 152, 024122 (2020).  
[pdf](https://huanghua1994.github.io/files/JCP-GTFock-Huang-Sherrill-Chow.pdf){: .btn} [AIP](https://pubs.aip.org/aip/jcp/article/152/2/024122/317608/Techniques-for-high-performance-construction-of){: .btn}

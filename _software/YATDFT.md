---
title: "YATDFT: Yet Another Tiny DFT Library"
collection: software
excerpt: "YATDFT is a tiny library for constructing matrices used in restricted closed shell Hartree-Fock (HF) and Kohn-Sham density functional theory (KS-DFT) self-consistent field (SCF) calculations using Gaussian basis sets."
---

[YATDFT](https://github.com/huanghua1994/YATDFT) is a tiny library for constructing matrices used in restricted closed shell Hartree-Fock (HF) and Kohn-Sham density functional theory (KS-DFT) self-consistent field (SCF) calculations using Gaussian basis sets.

<!---more--->
YATDFT is written in C and parallelized using OpenMP. The code of YATDFT is clean and well documented. YATDFT can be viewed as a simplified single-node version of [GTFock](https://github.com/gtfock-chem/GTFock) (GTFock cannot construct DFT exchange-correlation matrix yet).

YATDFT can construct:

* Core Hamiltonian matrix (Hcore)
* Overlap matrix (S)
* Basis transformation matrix (X)
* Coulomb matrix (J), using direct method or density fitting
* HF exchange matrix (K), using direct method or density fitting
* DFT exchange-correlation matrix (XC)
  * Built-in LDA XC functionals: Slater exchange, Slater Xalpha correlation ($\alpha = 0.7 - 2/3$), PZ81 correlation , PW92 correlation  
  * Built-in GGA XC functionals: PBE exchange & correlation, B88 exchange, LYP correlation
  * GGA XC functionals from Libxc: PW91 exchange & correlation, G96 exchange, PW86 exchange, P86 correlation
* CDIIS Pulay mixing for Fock matrix
* Density matrix (D), from Fock matrix or SAD initial guess

YATDFT also includes a demo code (`tests/AnySCF.c`) for running SCF calculation using different combinations of J/K/XC matrix construction methods

YATDFT includes most of the optimizations in my papers. If you use YATDFT in your work, please cite the following papers:

1. **Hua Huang** and Edmond Chow, *Accelerating Quantum Chemistry with Vectorized and Batched Integrals*, International Conference for High Performance Computing, Networking, Storage, and Analysis (SC18), Dallas, TX, Nov. 11-16, 2018
2. **Hua Huang**, C. David Sherrill, and Edmond Chow, *Techniques for High-Performance Construction of Fock Matrices*, Journal of Chemical Physics, **152**, 024122 (2020)

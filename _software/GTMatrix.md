---
title: "GTMatrix: Portable and Lightweight PGAS Matrix Library"
collection: software
excerpt: "GTMatrix is a portable and lightweight PGAS (partitioned global address space) matrix library written in C + MPI-3."
---

[GTMatrix](https://github.com/gtfock-chem/GTMatrix) is a portable and lightweight PGAS (partitioned global address space) matrix library written in C + MPI-3.
<!---more--->
GTMatrix is used in [GTFock](https://github.com/gtfock-chem/GTFock) library to replace the [Global Arrays](https://hpc.pnl.gov/globalarrays/) library. GTMatrix provides fundamental functionality:

* Distributed storage of a global matrix
* One-sided communication access (get, put, accumulate) to a global matrix
* Distributed task counter

GTMatrix supports three access modes:

* Blocking access
* Nonblocking access
* Batch access (new, not available in other PGAS frameworks)

If you use GTMatrix in your work, please cite the following paper:

**Hua Huang**, C. David Sherrill, and Edmond Chow, *Techniques for High-Performance Construction of Fock Matrices*, Journal of Chemical Physics, **152**, 024122 (2020)

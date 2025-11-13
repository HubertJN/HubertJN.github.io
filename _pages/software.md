---
permalink: /software/
title: "Software"
excerpt: "Software"
author_profile: true
redirect_from: 
  - /codes/
---

I have experience of developing scientific software in Python, C, C++, and Fortran. Often these are small codes performing analysis of simulation outputs and/or toy calculations, but I also develop and release my own packages on [GitHub](https://github.com/hubertjn). I have experience of developing codes suitable for deployment on high-performance computing facilities, including use of both shared memory (OpenMP) and distributed memory (MPI) parallelism. I also have experience in the use of Nvidia's CUDA platform for acceleration, as well as the use of PyTorch for custom ML implementations. If you are interested in working with me on a software project, please [email me](mailto:hubert.naguszewski@warwick.ac.uk)!

Codes Developed
-----
* [committor-predictor](https://github.com/HubertJN/committor-predictor), released open-source under the GNU Lesser General Public License (LGPL). (Still a work in progress)
  * A package for committor prediction for the 2D Ising model which involves:
    * Data curation for uniform distribution in committor values for optimal training.
    * Use of a custom Residual Convolutional Neural Network for classification.
    * Interpetability analysis for physical insight fron machine-learned predictions.

Code Contributions
-----
* [BraWl](https://github.com/ChrisWoodgate/BraWl), released open-source under the GNU Lesser General Public License (LGPL).
  * A package for performing lattice-based atomistic simulations of alloys with an internal energy given by a Bragg-Williams Hamiltonian. The package implements a range of conventional and enhanced sampling techniques. I have worked on this package in collaboration with [Chrisopher Woodgate My](https://chriswoodgate.github.io/), and my contributions include:
    * The implementation of a highly parallelised [Wang-Landau sampling](https://en.wikipedia.org/wiki/Wang_and_Landau_algorithm) algorithm.
    * The implementation of post-processing and plotting scripts for analysis.

* [GASP](https://github.com/dquigley533/GASP).
  * A package for GPU accelerated simulations of the 2D Ising model for nucleation studies. It exploits the massive parallelism of a GPU to run thousands (or tens of thousands) of realisations of the 2D Ising model concurrently. My contributions included:
    * Data output formatting for handling large datasets with HDF5.
    * Creating a fork for HPC cluster use, which includes scripts for trajectory generation, data selection, and committor calculation.

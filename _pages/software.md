---
permalink: /software/
title: "Software"
excerpt: "Software"
author_profile: true
redirect_from: 
  - /codes/
---

I have experience of developing scientific software in Python, C, C++, and Fortran. Often these are small codes performing analysis of simulation outputs and/or toy calculations, but I also develop and release my own packages on [GitHub](https://github.com/hubertjn). I have experience of developing codes suitable for deployment on high-performance computing facilities, including use of both shared memory (OpenMP) and distributed memory (MPI) parallelism. I also have experience in the use of Nvidia's CUDA platform for acceleration, as well as the use of PyTorch for custom ML implementations. If you are interested in working with me on a software project, please [email me](mailto:hubert.naguszewski@warwick.ac.uk)!

Professional / Research software
-----

### Codes developed
* **[committor-predictor](https://github.com/HubertJN/committor-predictor)** (LGPL; work in progress)  
  A package for committor prediction for the 2D Ising model, including:
  * Data curation to achieve a more uniform distribution in committor values for training
  * A custom residual convolutional neural network for classification
  * Interpretability analysis to extract physical insight from model predictions
  * Automated training/validation workflows suitable for HPC batch execution

### Code contributions
* **[BraWl](https://github.com/ChrisWoodgate/BraWl)** (LGPL)  
  A lattice-based atomistic simulation package for alloy thermodynamics with a Bragg–Williams Hamiltonian and conventional/enhanced sampling methods. My contributions include:
  * Implementation and optimisation of a highly parallelised Wang–Landau sampling workflow
  * Parallel performance profiling and scaling benchmarks (strong scaling tested to 96 CPU cores)
  * HPC automation via Slurm job scripts and parameter sweeps
  * Post-processing and plotting scripts for analysis

* **[GASP](https://github.com/dquigley533/GASP)**  
  GPU-accelerated simulations of the 2D Ising model for nucleation studies. My contributions include:
  * HDF5-based data output and storage for large-scale datasets
  * Scripts for trajectory generation, data selection, committor calculation, and nucleation-rate/error analysis
  * HPC cluster execution and monitoring via Slurm batch scripts

Hobby software
-----

* **[S.T.A.L.K.E.R. GAMMA Modpack](https://github.com/Grokitach/Stalker_GAMMA)** - Contributor (Nov 2024 - Feb 2025)  
  Fan-made modpack for the *S.T.A.L.K.E.R.* series (GSC Game World).
  * Delivered Lua scripting fixes and gameplay tweaks
  * Triaged issues and maintained the backlog; prioritised and resolved community-reported bugs
  * Coordinated with testers to validate patches across builds and reduce regressions


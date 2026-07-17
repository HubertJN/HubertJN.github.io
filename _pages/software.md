---
permalink: /software/
title: "Software"
excerpt: "Software"
author_profile: true
redirect_from: 
  - /codes/
---

I develop scientific software in Python, C, Fortran, and Bash for simulation, analysis, automation, and machine learning. My work includes high-performance computing workflows using MPI, OpenMP, Slurm, GCC, NVCC, Make, HDF5, and NetCDF, alongside GPU-accelerated data generation and PyTorch-based modelling. If you are interested in working with me on a software project, please [email me](mailto:hubert.naguszewski@warwick.ac.uk)!

Professional / Research software
-----

### Codes developed
* **[committor-predictor](https://github.com/HubertJN/committor-predictor)** (work in progress)  
  I developed CNN-based committor predictors for nucleation in the 2D Ising model, using GPU-accelerated brute-force simulations to generate over one million labelled microstates across multiple independently trained models.
  * Constructed Markov state models along learned reaction coordinates
  * Benchmarked nucleation rates against brute-force and largest-geometric-cluster baselines
  * Automated training, validation, and MSM workflows on Slurm-based HPC clusters
  * Analysed learned models to identify physically meaningful structure in the predictions

* **[lammps-benchmark](https://github.com/HubertJN/lammps-benchmark)**  
  I developed an automated parameter-optimisation suite in LAMMPS for a collaborator.
  * Fully automated Python command-line interface integrated with Slurm
  * Parameter sweeps and strong-scaling benchmarks up to 128 cores
  * Log parsing and metric aggregation for reproducible comparisons
  * PDF reporting script summarising optimal parameters and scaling behaviour

### Code contributions
* **[BraWl](https://github.com/ChrisWoodgate/BraWl)**  
  I co-developed a high-throughput Wang-Landau Monte Carlo simulation code for alloy thermodynamics and phase transitions.
  * Implemented and profiled parallel CPU performance
  * Benchmarked strong scaling to 96 cores
  * Optimised the choice of parallelisation strategy and helped finalise the 1.0 release
  * Used automated production runs on CentOS HPC clusters with Slurm scheduling for parameter sweeps

* **[GASP](https://github.com/dquigley533/GASP)**  
  I contributed to the GPU-accelerated scientific computing package GASP.
  * Implemented HDF5 data storage for 2D Ising simulation datasets used in ML training
  * Developed Python CLI tools for automated CUDA-accelerated data generation, curation, and ML dataset creation
  * Built multi-GPU Slurm workflows on CentOS HPC clusters

Hobby software
-----

### Code contributions
* **[S.T.A.L.K.E.R. GAMMA Modpack](https://github.com/Grokitach/Stalker_GAMMA)**  
  I delivered Lua scripting fixes and gameplay tweaks for a video game modpack.
  * Triaged bugs and maintained backlog items
  * Partnered with a tester team to validate patches across builds
  * Shipped fixes with attention to regressions and player-facing quality

---
permalink: /software/
title: "Software"
excerpt: "Software"
author_profile: true
redirect_from: 
  - /codes/
---

I have experience of developing scientific software in Python, C, and Fortran. Often these are small codes performing analysis of simulation outputs and/or toy calculations, but I also develop and release my own packages on [GitHub](https://github.com/hubertjn). I have experience of developing codes suitable for deployment on high-performance computing facilities, including use of both shared memory (OpenMP) and distributed memory (MPI) parallelism. I also have experience in the use of Nvidia's CUDA platform for acceleration, as well as the use of PyTorch for custom ML implementations. If you are interested in working with me on a software project, please [email me](mailto:hubert.naguszewski@warwick.ac.uk)!

Professional / Research software
-----

### Codes developed
* **[committor-predictor](https://github.com/HubertJN/committor-predictor)** (work in progress)  
  I built this to turn a research project into a repeatable pipeline for committor prediction in the 2D Ising model. The focus is on combining physically grounded ML with interpretable outputs that are useful beyond a single dataset. Very much still a work in progress.
  * Data engineering and preprocessing to curate balanced training sets across committor values
  * Custom residual CNN implementation for classification, with reproducible training runs
  * Model interpretability and error analysis to extract physically meaningful signals from predictions
  * Automated training/validation workflows for Linux HPC clusters (Slurm), suitable for batch execution

* **[lammps-benchmark](https://github.com/HubertJN/lammps-benchmark)** (work in progress)  
  This started as a way to speed up a collaborator's LAMMPS run and grew into a small performance engineering toolkit. My goal is to make benchmarking, parameter tuning, and scaling analysis fast, repeatable, and easy to compare across runs.
  * Slurm-driven automation for a manual baseline run plus repeatable benchmarking workflows
  * Parameter sweeps over key simulation controls (`ks`, `kacc`, `dcut`) to optimize time-to-solution
  * Core scaling analysis via generated `job.slurm` scripts
  * Log parsing and metric aggregation into consolidated JSON summaries for reproducible comparisons
  * Automated reporting that produces a ranked PDF review (speedups, timing breakdowns, timeout handling)

### Code contributions
* **[BraWl](https://github.com/ChrisWoodgate/BraWl)**  
  I contributed to BraWl to make enhanced sampling workflows practical on real HPC systems. Most of my work focused on parallel performance, automation, and analysis so simulations could scale cleanly and produce reliable thermodynamic results.
  * Implemented and optimized a highly parallel Wang-Landau sampling workflow (HPC-focused scientific software)
  * Performance profiling, strong-scaling benchmarks, and throughput optimization (tested to 96 CPU cores)
  * Slurm automation with parameter sweeps and repeatable batch workflows on Linux clusters
  * Post-processing, analysis, and plotting scripts to support reproducible results and reporting

* **[GASP](https://github.com/dquigley533/GASP)**  
  I worked on GASP to support GPU-accelerated nucleation simulations and the downstream data workflows they require. My contributions centered on scalable data output, analysis tooling, and HPC execution so results could be generated and validated efficiently.
  * Implemented HDF5-based data output pipelines for large-scale dataset generation and storage
  * Built Python analysis tooling for trajectory generation, data selection, committor calculation, and uncertainty/error analysis
  * Automated HPC job submission and monitoring via Slurm batch scripts (CPU/GPU workflows)

Hobby software
-----

### Code contributions
* **[S.T.A.L.K.E.R. GAMMA Modpack](https://github.com/Grokitach/Stalker_GAMMA)**  
  I contributed here because I enjoyed the modpack and wanted to give back to the community. It involved working in a collobratibe environment with fast-feedback development in a small but dedicated community team. It's a good outlet for shipping small fixes quickly, doing practical debugging, and improving quality for players.
  * Delivered Lua scripting fixes and gameplay tweaks with regression-aware iteration
  * Issue triage and backlog maintenance; prioritized and resolved community-reported bugs
  * Coordinated with testers to validate patches across builds and improve release quality

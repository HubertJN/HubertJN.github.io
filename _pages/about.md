---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year PhD student in the [Centre for Doctoral Training in Modelling of Heterogeneous Systems](https://warwick.ac.uk/fac/sci/hetsys/) at the University of Warwick, based in the Department of Physics under the supervision of Prof. David Quigley. My training included a one-year CDT programme covering materials simulation and predictive modelling techniques for a Postgraduate Diploma, and I specialise in enhanced Monte Carlo sampling and predictive machine learning for complex physical systems.

My current research has two avenues:

1. **Wang-Landau sampling and alloy thermodynamics**  
   I develop scalable variants of the Wang-Landau algorithm for calculating densities of states in alloy systems. This includes analysing the efficiency of different parallelisation strategies, improving load balancing across energy windows, and applying flat-histogram sampling to high-entropy alloy thermodynamics.

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/images/alloys.png" alt="Illustration of a low-temperature ordered high-entropy alloy (left), and of specific heat as well as atomic short-range order parameters for a high-entropy alloy (right).">
  <figcaption>Illustration of a low-temperature ordered high-entropy alloy (left), and of specific heat as well as atomic short-range order parameters for a high-entropy alloy (right).</figcaption>
</figure> 

2. **Machine learning for statistical physics**  
   I develop supervised convolutional neural-network models for committor prediction in the 2D Ising model. This work provides a practical alternative to expensive committor calculations, constructs Markov state models along learned reaction coordinates, and benchmarks nucleation rates against brute-force and geometric-cluster baselines.

My broader interests include algorithms for statistical mechanics, high-performance scientific computing, and interpretable machine learning for physical systems.

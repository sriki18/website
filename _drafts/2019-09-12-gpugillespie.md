---
title: Running Gillespie stochastic simulation algorithm on CUDA (using PyCUDA)
date: 2019-09-12 18:02:15 -0800
toc: true
toc_sticky: true
toc_label: Contents
permalink: /gpugillespie/
# header:
#   teaser: /assets/gpupoisson/gpu_poisson.png
---

<!---comment to remove Goal from showing up below teaser--->

# Goal

Implement the Gillespie stochastic simulation algorithm SSA on a CUDA device to solve a simple model. The GPU code will be written with CUDA C, and PyCUDA will be used as the higher level interface.

# Background

The stochastic simulation algorithm (SSA), also called the Direct method is based on _. It is used to simulate chemical kinetics in reactions with low numbers of molecules. Molecule numbers, instead of concentration or density, is modeled. The algorithm itself is introduced __here__.

The model use for demonstration is the following:

### TODO
1. Code up a simple model in CUDA (maybe A->B, B->C)
2. Make model plot with `python` after repeating model simulation.

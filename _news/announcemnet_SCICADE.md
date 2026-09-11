---
layout: post
date: 2026-06-30 00:00:00-0400
inline: true
related_posts: false
---
<b>[SCICADE 2026](https://scicade.org)</b>

I delivered an invited talk at this major international conference **``Scientific Computing and Differential Equations'' (SCICADE 2026)** at Session 10K: MS42.2: Artificial intelligence and scientific computing, chaired by Prof. Des Higham. My talk was titled, "**Generalization Bounds for PINNs Solving the Navier-Stokes Equations**" 

ABSTRACT. In this talk I will present our recent progress on establishing rigorous first-of-its-kind upper bounds on the generalization error for the method of approximating solutions to the (d+1)-dimensional incompressible Navier-Stokes equations by training depth-2 neural networks trained via the unsupervised Physics-Informed Neural Network (PINN) framework. This is achieved by bounding the Rademacher complexity of the PINN risk. For appropriately weight bounded net classes our derived generalization bounds do not explicitly depend on the network width and our framework characterizes the generalization gap in terms of the fluid's kinematic viscosity and loss regularization parameters. In particular, the resulting sample complexity bounds are dimension-independent. Our generalization bounds suggest using novel activation functions for solving fluid dynamics. We provide empirical validation of the suggested activation functions and the corresponding bounds on a PINN setup solving the Taylor-Green vortex benchmark.

Reference : [arXiv : 2603.23072](https://arxiv.org/abs/2603.23072)

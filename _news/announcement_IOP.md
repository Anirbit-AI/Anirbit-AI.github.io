---
layout: post
date: 2024-06-11 00:00:00-0400
inline: true
related_posts: false
---

<b>IOP-MLST!</b>

[Investigating the Ability of PINNs to Solve Burgers' PDE Near Finite-Time Blow Up](https://iopscience.iop.org/article/10.1088/2632-2153/ad51cd)

What is the relationship between an ML model's error in approximating the PDE solution and the risk of its PINN loss function? Recall 
that it's only the latter that the codes try to minimize. This is in general quite unclear - and in this latest work with my amazing 
collaborator Dibyakanti Kumar, we try to prove relationships between these two critical quantities, for non-viscous pressure-less fluids 
(Burgers' PDE in d-dimensions), while allowing for divergence of the flow.

This is an interesting edge because it allows for PDE solutions that blow-up in finite-time while starting from smooth initial 
conditions. Our way of analyzing this population risk leads to indications for why penalizing for the gradients of the surrogate (the 
net) has previously helped in such experiments. 


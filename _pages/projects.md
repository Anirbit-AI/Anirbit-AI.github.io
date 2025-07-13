---
layout: page
title: Focus Projects
permalink: /projects/
description: Ideas We Are Excited About!
nav: true
nav_order: 5
---

<style>
  .responsive-container {
    display: flex;
    align-items: center;
    gap: 20px;
  }

  @media (max-width: 768px) {
    .responsive-container {
      flex-direction: column;
      align-items: flex-start; /* optional, aligns text to the left */
    }
  }
</style>

<!-- _pages/publications.md -->
<div class="responsive-container">
<img src="/assets/img/finalized-2.png" alt="Publications Banner" style="width:175px; height:175px;"/>
 <div>
     <p style="margin-top: 5px;"> 
     Partial differential equations (PDEs) are the ubiquitous way to model various natural dynamics such as fluid flow or evolution of the quantum state of a molecule. Various sciences have a critical dependency on having fast and reliable numerical solvers for PDEs. However classical methods of simulating PDEs can be very expensive for very many instances of practical relevance. Hence large parts of the industry are trying to implement methods from Scientific-ML for these tasks. 
      </p> 
     <p style="margin-top: 5px;">
   In our group we seek to explore the foundational challenges of Scientific-ML via the lens of mathematics - and push the frontiers of both. We aim to prove (a) architecture requirements for neural PDE solving and (b) performance guarantees and (c) uncertainty quantification for (stochastic) first-order algorithms that can be deployed to train neural operators and nets for solving target PDEs and dynamical systems, in arbitrary dimensions.
     </p>
  </div>
</div>

<div>
 <p>  </p>
</div>
<div>
 <p>  </p>
</div>

<!-- _pages/publications.md -->
<div  class="responsive-container">
<img src="/assets/img/finalized.png" alt="Publications Banner" style="width:175px; height:175px;"/>
 <div>
  <h3> Mathematical Foundations of Scientific-ML (5 Works So Far.)</h3>
     <p style="margin-top: 5px;">
       <br>
     We gave the first-ever proof of,
       <br> <br>
       &nbsp; &nbsp; • <b> size lowerbounds for training PINNs with noisy data : </b> "Noisy PDE Training Requires Bigger PINNs", <a href="https://arxiv.org/abs/2507.06967"> Andre-Sloan et. al. (arXiv 2025)</a>
       <br> 
       &nbsp; &nbsp; • <b> true error bounds on PINNs solving PDEs with finite-time blow-up : </b> "Investigating the ability of PINNs to solve Burgers’ PDE near finite-time blowup", <a href="https://iopscience.iop.org/article/10.1088/2632-2153/ad51cd"> Dibyakanti Kumar and Anirbit Mukherjee (IOP-MLST 2024)</a>
      <br> 
      &nbsp; &nbsp; • <b> sample size requirements for operator learning : </b> "Towards Size-Independent Generalization Bounds for Deep Operator", <a href="https://openreview.net/pdf?id=21kO0u6LN0"> Gopalani et al. (TMLR 2024)</a>
      <br> 
      &nbsp; &nbsp; • <b> model size requirements for operator training : </b> "Size Lowerbounds for Deep Operator Networks", <a href="https://openreview.net/pdf?id=RwmWODTNFE"> Mukherjee et. al. (TMLR 2024)</a>
       <br> <br> 
      In the realm of empirical studies in Sci-ML,
      <br> <br>
       &nbsp; &nbsp; • <b> we gave one of the most extensive studies on how the PINN loss can be modified to exactly implement either boundary or initial conditions and their relative tradeoffs : </b> "Improving PINNs By Algebraic Inclusion of Boundary and Initial Conditions", <a href="https://arxiv.org/abs/2407.20741"> Ren et al. (arXiv 2024)</a>
   </p>
  </div>
</div>

<div>
 <p>  </p>
</div>

<!-- _pages/publications.md -->
<div  class="responsive-container">
<div style="display:flex;align-items;center; gap: 20px;">
<img src="/assets/img/finalized.png" alt="Publications Banner" style="width:175px; height:175px;"/>
 <div>
   <h3>  Provable Neural Training Algorithms </h3>
     <p style="margin-top: 5px;"> 
     </p>
 </div>
</div>
</div>


---
layout: post
date: 2024-12-5 00:00:00-0000
inline: true
related_posts: false
---

<b>Information & Inference : A Journal of the IMA!</b>

[Global Convergence of SGD On Two Layer Neural Nets](https://arxiv.org/abs/2210.11452)

This is one of our most interesting lines of work that has opened up a whole new mechanism for proving the convergence of noisy gradient based algorithms for neural nets. We have already had a TMLR paper in this theme - and more drafts in this topic are on the way. 
The crux of this work is that we isolate neural net loss functions - at constant regularization, at arbitrary size and for any data - that are ``Villani functions'' - hence their corresponding Gibbs' meaasures satisfy the Poincare inequalities. Thus, we have a first-of-its-kind result, of finding neural loss setups which induce isoperimetric inequalities. Very critically, in this work the amount of regularization needed is *independent of the number of gates* and only depends on the bounds of the data.

Given the identification of isoperimetry in neural setups, various recent results in mathematics can be used to get the convergence of noisy gradient methods to the global minima of such losses. In this work, we go via the observations in this [JMLR paper](https://jmlr.org/papers/v24/20-364.html). *Thus we have the first proof of convergent training of neural nets beyond the NTK regime*

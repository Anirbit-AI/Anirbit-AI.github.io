---
layout: post
date: 2024-12-2 00:00:00-0000
inline: true
related_posts: false
---

<b>TMLR! (for the 3rd time in 2024!)</b>

[Towards Size-Independent Generalization Bounds for Deep Operator Nets](https://openreview.net/pdf?id=21kO0u6LN0)

This work is the end result of a long project that was completed by my PhD student Dibyakanti Kumar. It was started with Pulkit Gopalani (PhD student in University of Michigan) and Sayar Karmakar (faculty in statistics at The University of Florida). The summary is this: *use Huber loss to solve PDEs* - it is likely to perform better and this hope has significant mathematical grounding. This work is a tour-de-force in Rademacher theory - for non-Lipschitz predictors. We showed that a very natural and relevant loss class of DeepONet have a size-independent generalization bound for well-tuned Huber losses. This arises out of showing that the underlying Rademacher complexity for the the DeepONets is itself width-independent and rather scales with a very complicated form of capacity measure. We believe that this work motivates a whole *lot* of future work about extending these results and testing its implications for the entire range of neural operators that are being thought about these days. 

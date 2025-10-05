---
layout: page
title: Data-driven scientific discovery
description: Unsupervised extraction of variables from data.
img: assets/img/cover_autoencoders.jpg
importance: 3
category: Machine Learning
related_publications: true
---

Interpretability is a central challenge in Artificial Intelligence. Why does a model say what it says? What factors influence its decisions? What does it really learn?

Under the advice of Prof. Gabriel B. Mindlin and working with his collaborator Prof. Pablo Groisman, we explored these questions using a neural network that trains itself on a video of a physical system, constrained to maximize information compression. What does it retain? Using rigorous mathematics, we show that the network learns the flow of the underlying dynamics, preserving the topological structure of the original system {% cite fainstein2023reconstruction %}{% cite fainstein2025reconstructing %}.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Fig_autoencoders.png" title="Fig 1" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Autoencoders processing spatiotemporal data. We show how to train it to obtain phase space representations in its latent space. 
</div>

This method contributes to tackle a key step in data driven model discovery: reliably obtaining the variables of the system from recorded data. The data can be high-dimensional or a partial measurement. More broadly, while machine learning applications usually focus on how to get more out of an architecture, the problem of interpretability, in all its forms, is a mathematically interesting question, and with no exaggeration, of existential importance. Our articles provide important steps in this direction.


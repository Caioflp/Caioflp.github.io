---
layout: page
title: Random Gradient-Free Optimization in Infinite Dimensional Spaces
description: Joint work with Yuri Saporito, Bernardo da Costa and Daniel Csillag (FGV EMAp)
img: assets/img/functional-sgd.png
importance: 1
category: EMAp
related_publications: false
---

This work is part of my master's thesis in applied mathematics at FGV EMAp.

In this paper, we propose a random gradient-free method for optimization in infinite dimensional Hilbert spaces, applicable to functional optimization in diverse settings.  Though such problems are often solved through finite-dimensional gradient descent over a parametrization of the functions, such as neural networks, an interesting alternative is to instead perform gradient descent directly in the function space by leveraging its Hilbert space structure, %seen as an infinite-dimensional separable Hilbert space, thus enabling provable guarantees and fast convergence. However, infinite-dimensional gradients are often hard to compute in practice, hindering the applicability of such methods. To overcome this limitation, our framework requires only the computation of directional derivatives and a pre-basis for the Hilbert space domain, i.e., a linearly-independent set whose span is dense in the Hilbert space. This fully resolves the tractability issue, as pre-bases are much more easily obtained than full orthonormal bases or reproducing kernels --- which may not even exist --- and individual directional derivatives can be easily computed using forward-mode scalar automatic differentiation. We showcase the use of our method to solve partial differential equations \emph{à la} physics informed neural networks (PINNs), where it effectively enables provable convergence.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/functional-sgd.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
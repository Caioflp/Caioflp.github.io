---
layout: page
title: Confidence intervals for HDI endpoints
description: Ongoing joint work with Luiz Carvalho, Yuri Saporito and Daniel Csillag (FGV EMAp), Flávio Bambirra (UFMG) and Charles Doss (University of Minnesota)
img: assets/img/hdi.png
importance: 4
category: EMAp
related_publications: false
---

When performing interval estimation for asymmetric probability distributions, especially those with hard constraints (at zero, say), commonly used central intervals may not appropriately convey uncertainty.    
In this scenario, highest density intervals (HDIs) -- that is, intervals with the minimal length for a given coverage -- are routinely used to summarise information about asymmetric probability distributions.
However, these intervals are usually estimated from (possibly dependent) samples of the target distribution, and, as far as we know, there exists no principled way in the literature to compute confidence intervals (asymptotic or not) for these estimates.
In this work, we propose to close this gap by providing an HDI estimator with accompanying asymptotic confidence intervals. 
Our approach consists in framing the HDI as a generalized $Z$-estimator, with a bi-dimensional criterion function $\Psi$ whose coordinates satisfy CLTs with different scaling factors.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hdi.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
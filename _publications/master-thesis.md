---
title: "Bootstrap-Based Robustness Analysis of Parameter Optimization in Climate Models Using QuadTune"
collection: publications
category: academics
excerpt: ""
permalink: /publication/master-thesis
date: 2025-01-01
paperurl: 'http://LuisHasenauer.github.io/files/Hasenauer_MS_Thesis.pdf'
citation: Luis Hasenauer. (2025). &quot;Bootstrap-Based Robustness Analysis of Parameter Optimization in Climate Models Using QuadTune.&quot; <i>tbd</i>. 1(1).'
---
Tuning the parameters of climate models is essential for improving their performance, but this process is often complicated by structural limitations, overfitting, and trade-offs between different regions or variables. This thesis combines the QuadTune optimization framework with nonparametric bootstrap resampling to analyze parameter uncertainty and identify tuning conflicts.
Bootstrap replicates of input metrics are used to generate empirical distributions of parameter estimates and construct nonparametric confidence intervals. Residuals from bootstraptuned parameters are compared with default and full-dataset residuals to assess spatial bias and model robustness.
A residual-based diagnostic method is introduced to detect tuning trade-offs by evaluating the minimum ℓ2 norm and correlation of residual pairs, resulting in a binary conflict map that highlights jointly untunable metrics.
The analysis focuses on the SWCF (shortwave cloud forcing) variable using 10,000 bootstrap samples over a 20◦ × 20◦ spatial grid. Results show that while QuadTune improves global performance, regional tuning conflicts and structural biases remain, highlighting limitations that cannot be addressed by parameter tuning alone.

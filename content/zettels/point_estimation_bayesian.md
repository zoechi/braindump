+++
title = "Point Estimation in Bayesian Statistics"
author = ["Jethro Kuan"]
lastmod = 2020-03-08T00:26:27+08:00
draft = false
+++

tags
: [§bayesian\_statistics]({{< relref "bayesian_statistics" >}})

Suppose we have a posterior distribution over parameters \\(\theta\\).
Sometimes, we would like to obtain a point estimate \\(\hat{\theta}\\) of
\\(\theta\\).

To do so, we may select a summary feature of \\(p(\theta | y)\\) such as
its mean, median or mode.

For symmetric posterior densities, the mean and median are equal. If
the posterior is also unimodal, then all 3 coincide.

For asymmetric posteriors, the median is often preferred. The mode
only considers the value corresponding to the maximum value of the
density, while the mean may give too much weight to extreme outliers.


## Backlinks {#backlinks}

-   [Interval Estimation in Bayesian Statistics]({{< relref "interval_estimation_bayesian" >}})

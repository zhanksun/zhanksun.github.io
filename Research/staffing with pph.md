---
title: 'Useful websites for COVID-19 research'
date: 2021-03-11
author: Zhankun Sun
permalink: /posts/2020/04/Covid-19/
tags:
  - Research
  - Covid-19
---

### Modeling Time-Varying Productivity with Applications in Physician Staffing in Emergency Departments

#### Stochastic modeling of a single physician
* $R(t)$: the number of reassess patients; $R(0)=R_0$
* $T(t)$: the number of reassess patients; $T(0)=T_0$
* $\mu_R$: the service rate for reassess
* $\mu_N$: the service rate for initial assessment
* $\theta$: the rate for delay in the test queue
* $C(t)$: physician capacity;
  * time-dependent due to EOS effect
* Can we model it using a finite-time CTMC? Or, **is it necessary?**
* Arena: simulation

<img src="/Research/AveragePPH.png" width="560">
<img src="/Research/Arena.png" width="560">
<img src="/Research/MD009.png" width="560">
<img src="/Research/MD009-32.png" width="560">


#### Statistical modeling (Poisson regression)
We can also apply statistical models to estimate the PPH: we can control MD ID, workload, learners, handovers taken,

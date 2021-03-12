---
title: 'Modeling Time-Varying Productivity and Its Applications in Physician Staffing in Emergency Departments'
date: 2021-03-12
author: Zhankun Sun
permalink: /posts/2021/03/PPH/
tags:
  - Research
  - Covid-19
---

### Modeling Time-Varying Productivity and Its Applications in Physician Staffing in Emergency Departments

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
We can also apply statistical models to estimate the PPH: we can control MD ID, workload, learners, handovers taken, current number of patients signed up,


### OM Literature
Zaerpour, Farzad, et al. "Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments." Available at SSRN 3519625 (2019).

Our paper's plot (**can we plot it with 30-minute resolution?**):
<img src="/Research/PPH_POM_Paper.png" width="800">

### Medical Literature
Wang, Biao, et al. "Physician shift behavior and its impact on service performances in an emergency department." 2013 Winter Simulations Conference (WSC). IEEE, 2013.

A plot from the above reference:

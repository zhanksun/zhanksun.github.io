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

### Medical Literature
Wang, Biao, et al. "Physician shift behavior and its impact on service performances in an emergency department." 2013 Winter Simulations Conference (WSC). IEEE, 2013.

A plot from the above reference:


### Empirical plots
<img src="/Research/Shifts.png" width="800">
<img src="/Research/Arrival_PPH.png" width="700">
<img src="/Research/Dist_MD_activity.png" width="500">
<img src="/Research/MD_activity_6.png" width="500">
<img src="/Research/MD_activity_7.png" width="500">
<img src="/Research/MD_activity_FT.png" width="500">
<img src="/Research/MD_activity_8.png" width="500">


I updated the estimates of arrival rates and PPH. There are some days that the information system is down. Hence, the recorded data are probamatic. The following days are removed from the estimates:
2015-01-29, 2015-02-26, 2015-03-26, 2015-04-30, 2015-05-28, 2015-06-25, 2015-07-30

All of them are 12:00 am on Thursdays, hence, I believe this is the scheduled maintenance time. Correspondingly, only the shifts S13, S14, and S15 are affected.

#### Probability of another round of reassess
<img src="/Research/R_probability.png" width="500">

Hence, the probability of going another round of test is 33.95%, i.e., 1/3.

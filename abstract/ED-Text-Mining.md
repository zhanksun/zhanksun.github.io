---
layout: archive
title: Topic Modeling on Triage Notes with Semi-Orthogonal Non-negative Matrix Factorization
permalink: /abstract/ED-Text-Mining
venue: by Yutong Li, Ruoqing Zhu, Annie Qu, Han Ye, Zhankun Sun
date: 2019
author_profile: true
---

Emergency Department (ED) crowding is a global issue that affects the efficiency of hospital management and patient care quality. It occurs when the request for an admit ward-bed to receive a patient is delayed until a doctor makes an admission decision. To potentially help reduce the overcrowding and waiting time of ED, we build a classifier to predict the disposition of patients using manually-typed nurse notes collected during triage provided by the Alberta Medical Center. Thereby allowing hospital staff to begin necessary preparation beforehand. However, these triage notes involve high dimensional, noisy, and also sparse text data, which makes model fitting and interpretation difficult. To address this issue, we propose a novel semi-orthogonal non-negative matrix factorization (SONMF) for both continuous and binary design matrices to reduce the dimensionality and derive word topics. There generated topic vectors provide the hospital with a direct interpretation of why the patient is visiting. Furthermore, we show that the classification performance can be improved by using the topic vectors as features, where our model has an advantage over other NMF methods. Real data analysis shows that the triage notes contain strong predictive information towards classifying the disposition of patients for certain medical complaints and has potential to help alleviate ED crowding.

**Keywords:** Emergency Department Crowding, Text Mining, Matrix Factorization, Dimension Reduction, Topic Modeling

---
layout: archive #archive
title: Publications
permalink: /publications/
author_profile: true
---

## Journal Publications

1. **Zhankun Sun**, Nilay T. Argon, Serhan Ziya, <q>Patient Triage and Prioritization Under Austere Conditions</q>. _Management Science_, 64(10):4471-4489, 2018. [\[pdf\]](/files/Sun-Argon-Ziya_Final.pdf) [\[Online Supplement\]](/files/mnsc.2017.2855-sm.pdf) (Former title: Priority scheduling of jobs with unknown types)
1. Bin Hu, **Zhankun Sun**, <q>Managing Self-Replicating Innovative Goods</q>. _Management Science, forthcoming_, 2020. [\[pdf\]](/files/replication_Final.pdf)
1. Yutong Li, Ruoqing Zhu, Annie Qu, Han Ye, **Zhankun Sun**, <q>Topic Modeling on Triage Notes With Semiorthogonal Nonnegative Matrix Factorization</q>. _Journal of the American Statistical Association_, 1-45, 2020. [\[pdf\]](https://arxiv.org/abs/1805.02306)
1. **Zhankun Sun**, Nilay T. Argon, Serhan Ziya, <q>When to Triage in Service Systems with Hidden Customer Class Identities?</q>. _Production and Operations Management_, 2021. [\[pdf\]](/files/Sun-Argon-Ziya-Arrival-POM.pdf)
1. Zhuang Zheng, **Zhankun Sun**, Jia Pan, Xiaowei Luo, <q>An Integrated Smart Home Energy Management Model Based on a Pyramid Taxonomy for Residential Houses With Photovoltaic-Battery Systems</q>. _Applied Energy_, 2021.

## Working Papers
* Wenhao Li, **Zhankun Sun**, L. Jeff Hong, <q>Who is Next: Patient Prioritization Under Emergency Department Blocking</q>. _Operations Research, second round revision_. [\[pdf\]](/files/Waiting Time Puzzle Revised.pdf)
* Farzad Zaerpour, Marco Bijvank, Huiyin Ouyang, **Zhankun Sun**, <q>Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments</q>. _Production and Operations Management, under 2nd round review_. [\[pdf\]](/files/Physician_Rostering_v4.pdf)
* Shuai Hao, **Zhankun Sun**, Yuqian Xu, <q>ED Triage: An Empirical Study of Fast-Track Admission</q>. _Working paper_.
  - Winner, Best Service Science Student Paper Award, 2020 INFORMS Conference on Service Science.

* Cheng Zhu, Beste Kucukyazici, **Zhankun Sun**,  Rick Mah, <q>Design of Specialist Response Policies in Hospital Emergency Departments</q>. _Working paper_.
* Huiyin Ouyang, **Zhankun Sun**, Junyang Wang, <q>Priority Scheduling When Job Type Information Is Not Free</q>. _Working paper_.
* Huiyin Ouyang, **Zhankun Sun**, Junyang Wang, <q>Impact of Classification Accuracy for Scheduling Jobs with Unknown Types in Service Systems</q>. _Working paper_.

## Conference

* Michele Foster, **Zhankun Sun**, Dongmei Wang, Grant Innes, Laurie-Ann Baker, Andrew McRae, Eddy Lang, <q>Optimal Shift Duration for Emergency Physician Efficiency, Effectiveness and Safety: A Comparison of 6, 7, and 8-hour Shifts</q>. _Canadian Association of Emergency Physicians Annual Conference_. Edmonton, 2015. [\[Abstract\]](https://cumming.ucalgary.ca/sites/default/files/teams/127/abs.%20optimal-shift-duration-for-em-physician-efficiency-foster-abstract-2015.pdf) [\[pdf\]](/files/abs. optimal-shift-duration-for-em-physician-efficiency-foster-abstract-2015.pdf)


<!---
## Working in Progress
* Huiyin Ouyang, **Zhankun Sun**, <q>On Scheduling a Two-Class Queue with Concave Waiting Cost</q>. _Working paper_.
* <q>Allocation of Intensive Care Unit Beds with Patient Abandonment and Readmission</q>, with H. Ouyang.
* <q>Admission Control under Imperfect Customer Information</q>, with H. Ouyang.
* <q>Mining Triage Notes to Predict Hospital Admissions from Emergency Departments</q>, with H. Ye, et al.

<ol start="9">
    <li><q>Allocation of Intensive Care Unit Beds with Readmission</q>, with H. Ouyang.</li>
    <li><q>Admission Control under Imperfect Customer Information</q>, with H. Ouyang.</li>
    <li><q>Mining Triage Notes to Predict Hospital Admissions from Emergency Departments</q>, with H. Ye, et al.</li>
</ol>
--->

{% if author.googlescholar %}
  You can also find my articles on <u><a href=</q>{{author.googlescholar}}</q>>my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

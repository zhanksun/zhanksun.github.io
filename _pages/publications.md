---
layout: archive #archive
title: Publications
permalink: /publications/
author_profile: true
---

## Journal Publications

1. Zhankun Sun, Nilay T. Argon, Serhan Ziya, <a href="https://doi.org/10.1287/mnsc.2017.2855" style="color: inherit; text-decoration: underline;text-decoration-style: solid;">Patient Triage and Prioritization Under Austere Conditions</a>. _Management Science_, 64(10):4471-4489, 2018. [\[pdf\]](/files/Sun-Argon-Ziya_Final.pdf) (Former title: Priority scheduling of jobs with unknown types)
  * Featured by <a href="https://www.informs.org/Blogs/ManSci-Blogs/Management-Science-Review/Patient-Triage-and-Prioritization-Under-Austere-Conditions" style="color: inherit;">Management Science Review</a>
2. Bin Hu, Zhankun Sun, <a href="https://doi.org/10.1287/mnsc.2020.3936" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">Managing Self-Replicating Innovative Goods</a>. _Management Science_, 2020. [\[pdf\]](/files/MS-replication-final.pdf)
3. Yutong Li, Ruoqing Zhu, Annie Qu, Han Ye, Zhankun Sun, <a href="https://doi.org/10.1080/01621459.2020.1862667" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">Topic Modeling on Triage Notes with Semiorthogonal Nonnegative Matrix Factorization</a>. _Journal of the American Statistical Association_, 1-16, 2020.
4. Zhankun Sun, Nilay T. Argon, Serhan Ziya, <a href="https://doi.org/10.1111/poms.13494" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">When to Triage in Service Systems with Hidden Customer Class Identities?</a>. _Production and Operations Management_, 2021. [\[pdf\]](/files/Sun-Argon-Ziya-Arrival-POM.pdf)
5. Wenhao Li, Zhankun Sun, L. Jeff Hong, <a href="https://zhanksun.github.io/publications/" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">Who Is Next: Patient Prioritization under Emergency Department Blocking</a>. _Operations Research, accepted_, 2021. [\[pdf\]](/files/Waiting_Time_Puzzle_final.pdf)
6. Zhuang Zheng, Zhankun Sun, Jia Pan, Xiaowei Luo, <a href="https://doi.org/10.1016/j.apenergy.2021.117159" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">An Integrated Smart Home Energy Management Model Based on a Pyramid Taxonomy for Residential Houses with Photovoltaic-Battery Systems</a>. _Applied Energy_, 2021.
7. Farzad Zaerpour, Marco Bijvak, H. Ouyang, Zhankun Sun, <q>Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments</q>. _Production and Operations Management, 3rd round review_. [\[pdf\]](/files/Physician_Rostering_POM.pdf)
8. Shuai Hao, Zhankun Sun, Yuqian Xu, <q>Emergency Care Access vs. Quality: An Empirical Analysis of Fast-Track Routing Decisions</q>. _Working paper_.
  * Winner, Best Service Science Student Paper Award, 2020 INFORMS Conference on Service Science.
9. H. Ouyang, Zhankun Sun, Junyang Wang, <q>Priority Scheduling When Job Type Information Is Not Free</q>. _Working paper_.
10. Cheng Zhu, Beste Kucukyazici, Zhankun Sun,  Rick Mah, <q>Design of Specialist Response Policies in Hospital Emergency Departments</q>. _Working paper_.
11. H. Ouyang, Zhankun Sun, <q>Models and Insights from Time-Varying Physician Productivity in Emergency Departments</q>. _Working paper_.

## Medical Papers
12. Michele Foster, Zhankun Sun, Dongmei Wang, Grant Innes, Laurie-Ann Baker, Andrew McRae, Eddy Lang, <q>Optimal Shift Duration for Emergency Physician Efficiency, Effectiveness and Safety: A Comparison of 6, 7, and 8-hour Shifts</q>. _Canadian Journal of Emergency Medicine_. P209, 2015. [\[Abstract\]](https://nbtrauma.ca/wp-content/uploads/2020/10/Phelna-et-al-2015.pdf) [\[pdf\]](/files/optimal-shift-duration-for-em-physician-efficiency-foster-abstract-2015.pdf)
13. H. Ouyang, Junyan Wang, Zhankun Sun, Eddy Lang, <q>The Impact of Emergency Department Crowding on Admission Decisions and Patient Outcome</q>. _Under review_. 2021.

{% if author.googlescholar %}
<!---
6. Huiyin Ouyang, **Zhankun Sun**, Junyang Wang, <q>Impact of Classification Accuracy for Scheduling Jobs with Unknown Types in Service Systems</q>. _Working paper_.
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
  You can also find my articles on <u><a href=</q>{{author.googlescholar}}</q>>my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

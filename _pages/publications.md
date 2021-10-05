---
layout: archive
title: Publications
permalink: /publications/
author_profile: true
---

## Journal Publications

1. Sun, Z., Argon, N.T., and Ziya, S., 2018. <a href="https://doi.org/10.1287/mnsc.2017.2855" style="color: inherit; text-decoration: underline;text-decoration-style: solid;">Patient Triage and Prioritization Under Austere Conditions</a>. _Management Science_, 64(10), 4471-4489. [\[pdf\]](/files/Sun-Argon-Ziya_Final.pdf) (Former title: Priority scheduling of jobs with unknown types)
  * Featured by <a href="https://www.informs.org/Blogs/ManSci-Blogs/Management-Science-Review/Patient-Triage-and-Prioritization-Under-Austere-Conditions" style="color: inherit;">Management Science Review</a>
2. Hu, B. and Sun, Z., 2020. <a href="https://doi.org/10.1287/mnsc.2020.3936" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">Managing Self-Replicating Innovative Goods</a>. _Management Science_. [\[pdf\]](/files/MS-replication-final.pdf)
2. Hu, B. and Sun, Z., 2020. [Managing Self-Replicating Innovative Goods](https://doi.org/10.1287/mnsc.2020.3936). _Management Science_. [\[pdf\]](/files/MS-replication-final.pdf)
3. Li, Y., Zhu, R., Qu, A., Ye, H., and Sun, Z., 2020. <a href="https://doi.org/10.1080/01621459.2020.1862667" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">Topic Modeling on Triage Notes with Semiorthogonal Nonnegative Matrix Factorization</a>. _Journal of the American Statistical Association_, 1-16.
4. Sun, Z., Argon, N.T., and Ziya, S., 2021. <a href="https://doi.org/10.1111/poms.13494" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">When to Triage in Service Systems with Hidden Customer Class Identities?</a>. _Production and Operations Management_. [\[pdf\]](/files/Sun-Argon-Ziya-Arrival-POM.pdf)
5. Li, W., Sun, Z., and Hong, L.J., 2021. <a href="https://zhanksun.github.io/publications/" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">Who Is Next: Patient Prioritization under Emergency Department Blocking</a>. _Operations Research, Accepted_. [\[pdf\]](/files/Waiting_Time_Puzzle_final.pdf)
6. Zaerpour, F., Bijvak, M., Ouyang, H., and Sun, Z., 2021. <a href="https://doi.org/10.1111/poms.13571" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments</a>. _Production and Operations Management_. [\[pdf\]](/files/Physician_Rostering_POM.pdf)
7. Zheng, Z., Sun, Z., Pan, J., and Luo, X., 2021. <a href="https://doi.org/10.1016/j.apenergy.2021.117159" style="color: inherit; text-decoration: underline;text-decoration-style: solid;text-decoration-color:initial;">An Integrated Smart Home Energy Management Model Based on a Pyramid Taxonomy for Residential Houses with Photovoltaic-Battery Systems</a>. _Applied Energy_.
8. H. Ouyang, Zhankun Sun, <q>Modeling Time-Varying Physician Productivity with Applications to Emergency Department Staffing</q>. _Working paper_.
9. Shuai Hao, Zhankun Sun, Yuqian Xu, <q>Emergency Care Access vs. Quality: Uncovering Hidden Consequences of Fast-Track Routing Decisions</q>. _Working paper_.
  * Winner, Best Service Science Student Paper Award, 2020 INFORMS Conference on Service Science.
10. H. Ouyang, Zhankun Sun, Junyang Wang, <q>Priority Scheduling When Job Type Information Is Not Free</q>. _Working paper_.
11. Cheng Zhu, Beste Kucukyazici, Zhankun Sun,  Rick Mah, <q>Design of Specialist Response Policies in Hospital Emergency Departments</q>. _Working paper_.

## Medical Papers
12. Michele Foster, Zhankun Sun, Dongmei Wang, Grant Innes, Laurie-Ann Baker, Andrew McRae, Eddy Lang, <q>Optimal Shift Duration for Emergency Physician Efficiency, Effectiveness and Safety: A Comparison of 6, 7, and 8-hour Shifts</q>. _Canadian Journal of Emergency Medicine_. P209, 2015. [\[Abstract\]](https://nbtrauma.ca/wp-content/uploads/2020/10/Phelna-et-al-2015.pdf) [\[pdf\]](/files/optimal-shift-duration-for-em-physician-efficiency-foster-abstract-2015.pdf)
13. H. Ouyang, Junyan Wang, Zhankun Sun, Eddy Lang, <q>The Impact of Emergency Department Crowding on Admission Decisions and Patient Outcome</q>. _Under revision_. 2021.

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

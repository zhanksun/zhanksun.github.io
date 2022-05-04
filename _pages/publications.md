---
layout: archive
title: Publications
permalink: /publications/
author_profile: true
---

## Journal Paper

1. Sun, Z., Argon, N.T., and Ziya, S., 2018. [Patient Triage and Prioritization Under Austere Conditions](https://doi.org/10.1287/mnsc.2017.2855). _Management Science_, 64(10), 4471-4489. [\[pdf\]](/files/Sun-Argon-Ziya_Final.pdf) (Former title: Priority scheduling of jobs with unknown types)
  * Featured by <a href="https://www.informs.org/Blogs/ManSci-Blogs/Management-Science-Review/Patient-Triage-and-Prioritization-Under-Austere-Conditions" style="color: inherit;">Management Science Review</a>
2. Hu, B. and Sun, Z., 2021. [Managing Self-Replicating Innovative Goods](https://doi.org/10.1287/mnsc.2020.3936). _Management Science_, 68(1), 399-419. [\[pdf\]](/files/MS-replication-final.pdf)
3. Li, Y., Zhu, R., Qu, A., Ye, H., and Sun, Z., 2021. [Topic Modeling on Triage Notes with Semiorthogonal Nonnegative Matrix Factorization](https://doi.org/10.1080/01621459.2020.1862667). _Journal of the American Statistical Association_, 116(536), 1609-1624. [\[pdf\]](/files/JASA_Triage_Notes.pdf)
4. Sun, Z., Argon, N.T., and Ziya, S., 2021. [When to Triage in Service Systems with Hidden Customer Class Identities?](https://doi.org/10.1111/poms.13494). _Production and Operations Management_, 31(1), 172-193. [\[pdf\]](/files/Sun-Argon-Ziya-Arrival-POM.pdf)
5. Li, W., Sun, Z., and Hong, L.J., 2021. [Who Is Next: Patient Prioritization Under Emergency Department Blocking](https://doi.org/10.1287/opre.2021.2187). _Operations Research_. [\[pdf\]](/files/Waiting_Time_Puzzle_final.pdf)
	* Special Issue on Behavioral Queueing Science
	* Finalist, INFORMS Service Science Best Cluster Paper Award, 2021.
6. Zaerpour, F., Bijvak, M., Ouyang, H., and Sun, Z., 2021. [Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments](https://doi.org/10.1111/poms.13571). _Production and Operations Management_, 31(2), 645-667. [\[pdf\]](/files/Physician_Rostering_POM.pdf)
7. Zheng, Z., Sun, Z., Pan, J., and Luo, X., 2021. [An Integrated Smart Home Energy Management Model Based on a Pyramid Taxonomy for Residential Houses with Photovoltaic-Battery Systems](https://doi.org/10.1016/j.apenergy.2021.117159). _Applied Energy_, 298: 117159.
8. Ouyang, H., Wang, J., Sun, Z., and Lang, E., 2022. [The Impact of Emergency Department Crowding on Admission Decisions and Patient Outcomes](https://doi.org/10.1016/j.ajem.2021.10.049). _American Journal of Emergency Medicine_, 51, 163-168. [\[pdf\]](/files/ED_crowding_impact.pdf)
9. Wang, Z., Liu, R., Sun, Z., 2021. Physician Scheduling for Emergency Departments Under Time-Varying Demand and Patient Return. _IEEE Transactions on Automation Science and Engineering, Accept_.
10. Ouyang, H., Sun, Z., Wang, J., 2022. Priority Scheduling When Job Type Information Is Not Free. _Under review_.
11. Hao, S., Sun, Z., Xu, Y., 2021. [Emergency Care Access vs. Quality: Uncovering Hidden Consequences of Fast-Track Routing Decisions](https://zhanksun.github.io/publications/).
* Winner, Best Service Science Student Paper Award, 2020 INFORMS Conference on Service Science.
* Second Place, Best Student Paper Competition, 2022 POMS-HK International Conference
<!---
[\[pdf\]](/files/ED_Modeling_PPH.pdf)
-->

## Working Paper

<ol start="12">
    <li> Ouyang, H., Liu, R., Sun, Z., <q>Emergency Department Modeling and Staffing: Time-Varying Physician Productivity</q>. </li>
    <li> Zou, C., Sun, Z., <q>Accurate Modeling and Simulation of Emergency Department Operations</q>. </li>
</ol>


<!--
<li> Cheng Zhu, Beste Kucukyazici, Zhankun Sun, Rick Mah, <q>Design of Specialist Response Policies in Hospital Emergency Departments</q>. </li>
12. Michele Foster, Zhankun Sun, Dongmei Wang, Grant Innes, Laurie-Ann Baker, Andrew McRae, Eddy Lang, <q>Optimal Shift Duration for Emergency Physician Efficiency, Effectiveness and Safety: A Comparison of 6, 7, and 8-hour Shifts</q>. _Canadian Journal of Emergency Medicine_. P209, 2015. [\[Abstract\]](https://nbtrauma.ca/wp-content/uploads/2020/10/Phelna-et-al-2015.pdf) [\[pdf\]](/files/optimal-shift-duration-for-em-physician-efficiency-foster-abstract-2015.pdf)

## Conference Paper
<ol start="15">
    <li> Michele Foster, Zhankun Sun, Dongmei Wang, Grant Innes, Laurie-Ann Baker, Andrew McRae, Eddy Lang, <q>Optimal Shift Duration for Emergency Physician Efficiency, Effectiveness and Safety: A Comparison of 6, 7, and 8-hour Shifts</q>. <i>Canadian Journal of Emergency Medicine</i>. P209, 2015. <a href="https://nbtrauma.ca/wp-content/uploads/2020/10/Phelna-et-al-2015.pdf" style="color: inherit; text-decoration: underline;text-decoration-color:initial;">[Abstract]</a></li>
</ol>
-->

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

---
layout: archive #archive
title: Publications
permalink: /publications/
author_profile: true
---

## Publications & Working Papers

1. **Zhankun Sun**, Nilay T. Argon, Serhan Ziya, <q>Patient Triage and Prioritization Under Austere Conditions</q>. _Management Science_, 64(10):4471-4489, 2018. [\[pdf\]](http://zhanksun.github.io/files/Sun-Argon-Ziya_Final.pdf)
2. Bin Hu, **Zhankun Sun**, <q>Managing Self-Replicating Innovative Goods</q>. _Management Science, 2nd round review_. [\[pdf\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3345311)
3. **Zhankun Sun**, Nilay T. Argon, Serhan Ziya, <q>When to Triage in Service Systems with Hidden Customer Class Identities?</q>. _Production and Operations Management, in revision_. [\[pdf\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3346173)
4. Farzad Zaerpour, Marco Bijvank, **Zhankun Sun**, <q>Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments</q>. _Production and Operations Management, in revision_. [\[pdf\]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3519625)
5. Yutong Li, Ruoqing Zhu, Annie Qu, Han Ye, **Zhankun Sun**, <q>Semi-Orthogonal Non-Negative Matrix Factorization with an Application in Text Mining</q>. _Journal of the American Statistical Association, in revision_. [\[pdf\]](https://www.researchgate.net/profile/Jack_Yutong_Li/publication/325008975_Semi-Orthogonal_Non-Negative_Matrix_Factorization_with_an_Application_in_Text_Mining/links/5d1274f7458515c11cf88761/Semi-Orthogonal-Non-Negative-Matrix-Factorization-with-an-Application-in-Text-Mining.pdf)
6. Wenhao Li, **Zhankun Sun**, Jeff L. Hong, <q>Who's Next: Dynamic Patient Prioritization in an Emergency Department</q>. _Working paper_.
7. Shuai Hao, **Zhankun Sun**, Yuqian Xu, <q>Routing Under Congestion: An Empirical Study of Triage Drift in Emergency Departments</q>. _Working paper_.
8. Cheng Zhu, Beste Kucukyazici, **Zhankun Sun**,  Rick Mah, <q>Design of Specialist Response Policies in Emergency Departments: A Data-Driven Approach</q>. _Working paper_.


## Working in Progress

<ol start="9">
    <li><q>Admission Control under Imperfect Customer Information</q>, with H. Ouyang.</li>
    <li><q>Allocation of Intensive Care Unit Beds with Readmission</q>, with H. Ouyang.</li>
    <li><q>Priority Scheduling when Job Type Information is not Free</q>, with H. Ouyang.</li>
    <li><q>Mining Triage Notes to Predict Hospital Admissions from Emergency Departments</q>, with H. Ye, et al.</li>
</ol>


{% if author.googlescholar %}
  You can also find my articles on <u><a href=</q>{{author.googlescholar}}</q>>my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

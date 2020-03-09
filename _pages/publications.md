---
#layout: archive
title: </q>Publications</q>
permalink: /publications/
author_profile: true
---

## Publications & Working Papers

1. **Zhankun Sun**, Nilay T. Argon, Serhan Ziya, <q>Patient Triage and Prioritization Under Austere Conditions</q>. <var>Management Science</var>, 64(10):4471-4489, 2018.
2. Bin Hu, **Zhankun Sun**, <q>Managing Self-Replicating Innovative Goods</q>. <var>Management Science, major revision</var>.
3. **Zhankun Sun**, Nilay Tan\i k Argon, Serhan Ziya, <q>When to Triage in Service Systems with Hidden Customer Class Identities?</q>. <var>Production and Operations Management, major revision</var>.
4. Farzad Zaerpour, Marco Bijvank, **Zhankun Sun**, <q>Scheduling of Physicians with Time-Varying Productivity Levels in Emergency Departments</q>. <var> Production and Operations Management, major revision</var>.
5. Yutong Li, Ruoqing Zhu, Annie Qu, Han Ye, **Zhankun Sun**, <q>Semi-Orthogonal Non-Negative Matrix Factorization with an Application in Text Mining</q>. <var> Journal of the American Statistical Association, major revision</var>.
6. Wenhao Li, **Zhankun Sun**, Jeff L. Hong, <q>Who's Next: Dynamic Patient Prioritization in an Emergency Department</q>. <var>Working paper</var>.
7. Shuai Hao, Yuqian Xu, **Zhankun Sun**,<q>Routing Under Congestion: An Empirical Study of Triage Drift in Emergency Departments</q>. <var>Working paper}.
8. Cheng Zhu, Beste Kucukyazici, **Zhankun Sun**,  Rick Mah, <q>Design of Specialist Response Policies in Emergency Departments: A Data-Driven Approach</q>. <var> Working paper}.


## Working in Progress

  1. List item one
  2. List item two
  9. Huiyin Ouyang, **Zhankun Sun**, <q>Priority Scheduling when Job Type Information is not Free</q>. <var>Working paper</var>.
  10. **Zhankun Sun**, Han Ye, Dongmei Wang, Haipeng Shen, Eddy Lang, <q>Mining Triage Notes to Predict Hospital Admissions from Emergency Departments</q>. <var> Working paper}.

{% if author.googlescholar %}
  You can also find my articles on <u><a href=</q>{{author.googlescholar}}</q>>my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

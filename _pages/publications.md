---
#layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Publications & Working Papers

1. {\bf Zhankun Sun}, Nilay Tan\i k Argon, Serhan Ziya, ``Patient Triage and Prioritization Under Austere Conditions''. {\itshape Management Science}, 64(10):4471-4489, 2018.
2. List item two
3. List item three
4. List item four


## Ordered List (Nested)

  1. List item one
  2. List item two
  3. List item three
  4. List item four

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

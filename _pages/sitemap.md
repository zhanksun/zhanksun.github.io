---
layout: archive
title: "My Posts"
permalink: /sitemap/
author_profile: true
---

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}

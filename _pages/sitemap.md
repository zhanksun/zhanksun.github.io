---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

<h2>Posts</h2>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% capture written_label %}'None'{% endcapture %}

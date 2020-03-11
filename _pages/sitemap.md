---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site.

<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

<h2>Posts</h2>
{% for post in site.posts %}
  {% include post.md %}
{% endfor %}

{% for post in collection.docs %}
  {% unless collection.output == false or collection.label == "posts" %}
  {% include archive-single.html %}
  {% endunless %}
{% endfor %}

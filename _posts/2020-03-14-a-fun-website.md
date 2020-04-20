---
title: 'Websites for fun'
date: 2020-03-14
permalink: /posts/2020/03/a-fun-website/
tags:
  - cool posts
  - for fun
  - website
---

### A list of fun websites

1. [How New Jersey’s First Coronavirus Patient Survived](https://www.nytimes.com/2020/04/05/magazine/first-coronavirus-patient-new-jersey.html?smtyp=cur&smid=fb-nytimes&fbclid=IwAR3RHBuxIyZiztTSFzgg1ZzGfultb3MOzuaNyaqmn6JrUBA17LtlTsfwJ1k)
1. [Don't fall asleep at work!](https://www.facebook.com/FirstResponsePhotography/videos/505550817000094/) A call center example
1. [武漢戰疫全景紀錄片——《英雄之城》](https://www.facebook.com/MFAofficeHK/videos/170527003950822/UzpfSTE1NjQ2ODYyNzgzNDU1ODoxNjk5MTQ3NTgwMjMzMzE0/)
1. [Dim sum dough magic](https://www.facebook.com/scmp/videos/2668404036729199)


<!-- Comments -->
{% if site.data.comments[page.slug] %}
    <h3>
    {% if site.data.comments[page.slug].size > 1 %}
      {{ site.data.comments[page.slug] | size }}
    {% endif %}
    Comments:
    </h3>
  {% assign comments = site.data.comments[page.slug] | sort %}
    {% for comment in comments %}
      <label>
        {% if comment[1].url %}
          <a href="{{ comment[1].url }}">
        {% endif %}
        <strong>{{ comment[1].name }}</strong>
        {% if comment[1].url %}
          </a>
        {% endif %}
      </label>
      <em>{{ comment[1].date | date: "%B %d, %Y" }}</em>
      <p>{{ comment[1].message | markdownify }}</p>
    {% endfor %}
{% endif %}
<!-- Comments Form -->
  <form method="POST" action="{{ site.staticman_url }}">
    <input name="options[redirect]" type="hidden" value="https://example.com">
    <input name="options[slug]" type="hidden" value="{{ page.slug }}">
      <label>Name</label>
      <input name="fields[name]" type="text">
      <label>E-mail (optional)</label>
      <input name="fields[email]" type="email">
      <label>Website (optional)</label>
      <input name="fields[url]" type="url">
      <label>Message</label>
      <textarea style="width:100%" name="fields[message]" rows="12"></textarea>
      <small>Comments will appear after moderation.</small>
      <button type="submit">Submit comment</button>
  </form>

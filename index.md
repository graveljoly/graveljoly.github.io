---
layout: default
title: Home
---

{% for post in site.posts %}
  <article>
    <p style="font-size: small; color: grey;">{{ post.date | date: "%B %d, %Y" }}</p>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  </article>
{% endfor %}

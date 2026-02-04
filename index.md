---
layout: default
title: Home
---

# Recent Posts

{% for post in site.posts %}
  <div style="margin-bottom: 1.5em;">
    <h2 style="margin: 0;">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h2>
    <p style="margin: 0; font-size: small; color: grey;">
      {{ post.date | date: "%b %d, %Y" }}
    </p>
  </div>
{% endfor %}

---
layout: page
title: Blog
permalink: /blog/
eyebrow: Insights
description: Notes from Anthyia Consulting on compliance, automation, governance, and controlled delivery.
---

<div class="post-list full">
  {% for post in site.posts %}
    <a class="post-card" href="{{ post.url | relative_url }}">
      <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%d %B %Y" }}</time>
      <strong>{{ post.title }}</strong>
      <p>{{ post.description }}</p>
    </a>
  {% endfor %}
</div>

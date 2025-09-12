---
layout: default
title: Blog
pagination:
  enabled: true
permalink: /blog/
---

<h2>All Posts</h2>
<ul class="post-list">
  {% for post in site.posts %}
  <li class="post-card">
    <a href="{{ post.url | relative_url }}" class="post-card-title">{{ post.title }}</a>
    {% if site.theme_settings.show_post_dates %}
      <span class="post-card-date">{{ post.date | date: "%b %d, %Y" }}</span>
    {% endif %}
    <p class="post-card-excerpt">{{ post.excerpt | strip_html | truncate: 140 }}</p>
  </li>
  {% endfor %}
</ul>

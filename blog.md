---
layout: default
title: Blog
permalink: /blog/
---

# Technical Articles & Insights

Welcome to my blog where I share insights on control systems engineering, nuclear facility automation, and professional development in industrial automation.

## Latest Articles

{% if site.posts.size > 0 %}
  {% for post in site.posts %}
  <div class="post-card">
    <div class="post-date">{{ post.date | date: "%B %d, %Y" }}</div>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p class="post-excerpt">{{ post.excerpt }}</p>
    <a href="{{ post.url | relative_url }}" class="read-more">Read More →</a>
  </div>
  {% endfor %}
{% else %}
  <p>No articles published yet. Check back soon!</p>
{% endif %}

## Subscribe

Subscribe to the [RSS feed](/feed.xml) to receive notifications about new articles.

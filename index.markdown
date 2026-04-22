---
layout: default
title: Home
---

# Welcome to My Blog

This is my static blog. I'm (now) using the **Architect** theme with Jekyll markdown on GitHub Pages for this Web Deployment Assignment.

### Latest Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <span>({{ post.date | date: "%B %d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>



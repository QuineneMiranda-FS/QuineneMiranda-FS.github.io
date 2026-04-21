---
layout: default
title: Home
---

# Welcome to My Blog

This is my corner of the internet. I'm using the **Architect** theme with Jekyll markdown on GitHub Pages for this Web Deployment Assignment.

### Latest Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <span>({{ post.date | date: "%B %d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>

[View all posts]({{ "/archive" | relative_url }})

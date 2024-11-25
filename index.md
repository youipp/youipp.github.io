---
layout: default
title: Home
---
# {{ site.title }}
Welcome to Jekyll Testing!

## All Posts
{% for post in site.posts %}
- **Title:** [{{ post.title }}]({{ post.url }})  
  **Date:** {{ post.date | date: "%B %d, %Y" }}  
  **Excerpt:** {{ post.excerpt }}
{% endfor %}

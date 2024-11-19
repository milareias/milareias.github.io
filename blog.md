---
layout: default
title: Blog
---
[Home](./index.md) | [About Me](./about.md) | [Publications](./Publications.md) | [Contact](./contact.md) | [Projects](./projects.md) | [Blog](./blog.md)

# Blog

Welcome to my blog! Here are my latest posts:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

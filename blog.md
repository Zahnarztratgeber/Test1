---
layout: default
title: Blog
---

# Blog

{% raw %}
{% for post in site.posts %}
  ## [{{ post.title }}]({{ post.url }})
  <small>{{ post.date | date: "%d.%m.%Y" }}</small>

  {{ post.excerpt }}
{% endfor %}
{% endraw %}

---
layout: default
title: Blog
---

# Blog

{% raw %}
{% for post in site.posts %}
  ## [{{ post.title }}]({{ https://github.com/Zahnarztratgeber/Test1/blob/main/_posts/2026-02-12-zahnprovisorium-herausgefallen.md}})
  <small>{{ post.date | date: "%d.%m.%Y" }}</small>

  {{ post.excerpt }}
{% endfor %}
{% endraw %}

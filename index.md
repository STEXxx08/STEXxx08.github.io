---
layout: default
title: 欢迎来到我的博客
---

# 欢迎来到我的博客！

这里是我分享想法和经验的地方。你可以在下面找到我最新的文章：

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

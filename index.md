---
layout: default
title: GMY316
---

# 欢迎来到我的个人网站

## 最新文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>

## 快速导航

- [关于我](about.html)
- [笔记](notes.html)
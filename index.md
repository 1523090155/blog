---
layout: default
---

[书签页](https://shuqian.111600.xyz/)

[创建PAC](https://sspac.111600.xyz/)


# 学习

使用Jekyll 托管平台 搭建了我的博客站



<h1>最近的文章</h1>
<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}</li>
  {% endfor %}
</ul>




[网页格式](./another-page.html)



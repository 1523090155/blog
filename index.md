---
layout: default
---

<span style="background-color: #f0f0f0; padding: 10px; margin: 5px; border-radius: 5px;">
  <a href="https://shuqian.111600.xyz/">书签页</a>
</span>
<span style="background-color: #f0f0f0; padding: 10px; margin: 5px; border-radius: 5px;">
  <a href="https://sspac.111600.xyz/">创建PAC</a>
</span>


# 学习Jekyll建站

```
2025.4.3使用Jekyll+AI 搭建了博客站
```


<h1>文章</h1>
<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}</li>
  {% endfor %}
</ul>


[网页格式](./another-page.html)

## <a href="https://github.com/1523090155/blog" class="btn">View on GitHub</a>

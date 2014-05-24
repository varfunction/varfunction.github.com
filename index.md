---
layout: page
title: 请叫我红领巾!
tagline: Supporting tagline
---
{% include JB/setup %}

想写点什么东西来占住这空白的页面

好像并不是很容易

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

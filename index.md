---
layout: page
title: oceantang
tagline: Supporting tagline
---
{% include JB/setup %}

想写点什么东西来占住这空白的页面

好像并不是很容易

***不积跬步，无以至千里。不积小流，无以成江海。***
![home](assets/img/street.jpg)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date: '%Y-%m-%d' }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

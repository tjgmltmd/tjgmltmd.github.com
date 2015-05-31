---
layout: page
show_meta: false
subheadline: ""
title: "다른 종류의 웨어러블"
teaser: ""
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/kind/"
---


- [FOOTLOGGER](https://tjgmltmd.github.io//design/footlogger/)
- [SEATLOGGER](https://tjgmltmd.github.io//design/seatlogger/)



<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

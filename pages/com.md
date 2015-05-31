---
layout: page
show_meta: false
title: "웨어러블 기기비교"
subheadline: "Can I help you?"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/com/"
---


- [Mi Band & Fitbit charge](https://tjgmltmd.github.io//com/mivsfi/)
- [Galaxy Gear & G watch](https://tjgmltmd.github.io//com/gavsgw/)

<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

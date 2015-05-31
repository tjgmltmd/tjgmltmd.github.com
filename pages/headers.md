---
layout: page
show_meta: false
subheadline: "출시예정!"
title: "NEW WEARABLE"
teaser: "Footlogger/Seatlogger/Apple-watch sport  <em>Feeling Responsive</em> uses <a href='http://srobbin.com/jquery-plugins/backstretch/'>Backstretch by Scott Robin</a> expand them  from left to right. The width should be 1600 pixel or higher using a ratio like 16:9 or 21:9 or 2:1."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/headers/"
---


- [FOOTLOGGER](https://tjgmltmd.github.io//design/footlogger/)
- [SEATLOGGER](https://tjgmltmd.github.io//design/seatlogger/)
- [APPLE SPORTS WATCH](https://tjgmltmd.github.io//design/watchsport/)



<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

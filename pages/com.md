---
layout: page
show_meta: false
title: "웨어러블 기기비교"
subheadline: "Can I help you?"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/com/"
---


- [APPLE-I WATCH](https://tjgmltmd.github.io//design/apple-i-watch/)
- [SAMSUNG-GEAR](https://tjgmltmd.github.io//design/samsung-gear/)
- [CHARGEHR](https://tjgmltmd.github.io//design/chargeHR/)
- [LG-GWATCH](https://tjgmltmd.github.io//design/lg-gwatch/)
- [EPSON](https://tjgmltmd.github.io//design/epson/)
- [XIAOMI-MIBAND](https://tjgmltmd.github.io//design/meband/)
- [CAMCORDER](https://tjgmltmd.github.io//design/camcorder/)
- [FITBIT](https://tjgmltmd.github.io//design/fitbit/)


<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

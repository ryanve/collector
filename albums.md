---
title: Albums
permalink: /albums/index.html
---

{% for item in site.albums %}
  - [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}

---
title: Albums
---

{% for item in site.albums %}
  - [{{ item.title }}]({{ item.url }})
{% endfor %}

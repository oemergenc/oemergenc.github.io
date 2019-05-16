---
layout: default
title: Galleries (main page)
---

### Here are some galleries of projects i worked on:

{% for gallery in site.data.galleries %}
- [{{ gallery.description }}]({{ gallery.id }})
{% endfor %}

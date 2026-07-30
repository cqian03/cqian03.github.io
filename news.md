---
layout: page
permalink: /news/index.html
title: News & Updates
---

{% for item in site.data.news %}
- **{{ item.date }}:** {{ item.content }}
{% endfor %}

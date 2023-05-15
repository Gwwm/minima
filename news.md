---
layout: page
title: News
permalink: /news/
---

{% for item in site.data.news %}

## {{ item.title }}

{{ item.description }}
Date: {{ item.date }}
{% endfor %}

---
layout: page
title: People
permalink: /people/
---

{% for person in site.data.people %}

  <div class="person">
    <img src="{{ person.photo }}" alt="{{ person.name }}">
    <h2><a href="{{ person.webpage }}">{{ person.name }}</a></h2>
    <p>{{ person.title }}, {{ person.department }}, {{ person.area }}</p>
    <p>{{ person.bio }}</p>
  </div>
{% endfor %}

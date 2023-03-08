---
layout: default
permalink: /
title: "Florent Sarat personal site"
redirect_from:
  - /
---


{% for post in site.blogposts reversed %}
  {% include given-talk.html %}
{% endfor %}

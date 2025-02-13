---
layout: archive
permalink: /categories/ENGR_270_Speeches
title: "ENGR 270 Speeches"
author_profile: true
---

{% include base_path %}


{% for post in site.posts %}
  {% if post.categories contains "ENGR_270_Speeches" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
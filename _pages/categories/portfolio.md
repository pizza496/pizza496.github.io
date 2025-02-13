---
layout: archive
title: "Portfolio"
permalink: /categories/portfolio/
author_profile: true
---

{% include base_path %}

{% for post in site.posts %}
  {% if post.categories contains "portfolio" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
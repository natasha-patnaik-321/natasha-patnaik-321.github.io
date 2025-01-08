---
layout: archive
title: "Featured"
permalink: /featured/
author_profile: true
---

{% comment %}
<h2>The Design of Approximation Algorithms</h2>
{% for post in site.posts %}
  {% if post.categories contains "The Design of Approximation Algorithms" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Featured</h2>
{% for post in site.posts %}
  {% if post.categories contains "Featured" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
{% endcomment %}

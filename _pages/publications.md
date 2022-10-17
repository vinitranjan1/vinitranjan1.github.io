---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Working Papers
=====
"Performance Certification of First Order Methods for Parametric Quadratic Optimization". Joint with: B. Stellato.

Publications
=====

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

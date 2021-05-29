---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if https://philpapers.org/rec/GRIROC-4 %}
  You can also find my articles on <u><a href="{{https://philpapers.org/rec/GRIROC-4}}">my philpapers profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

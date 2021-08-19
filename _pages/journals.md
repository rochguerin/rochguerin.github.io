---
layout: archive
title: "Journals"
permalink: /journals/
author_profile: true
---

{% include base_path %}

{% for post in site.journals reversed %}
  {% include archive-single.html %}
{% endfor %}

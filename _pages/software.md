---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% include base_path %}

{% for post in site.software %}
  {% include archive-single.html %}
{% endfor %}

{% if post.excerpt != post.content %}
    <a href="{{ site.baseurl }}{{ post.url }}">Read more</a>
{% endif %}
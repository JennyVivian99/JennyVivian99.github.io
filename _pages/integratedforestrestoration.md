---
layout: archive
title: "Integrated Forest Restoration"
permalink: /integratedforestrestoration/
author_profile: true
---
{% include base_path %}

<ul>
  {% for post in site.integratedforestrestoration %}
    <li>
      <h2><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a></h2>
      <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

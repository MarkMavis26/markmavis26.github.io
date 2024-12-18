---
layout: default
title: Projects
---
<ul>
  {% assign sorted_projects = site.projects | sort: "order" %}
  {% for post in sorted_projects %}
    <li>
      <a href="{{ post.url }}" class="dark-link">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

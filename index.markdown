---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
tile: Blog
permalink: /blog/
---
<ul>
  {% assign sorted_posts = site.posts | sort: "order" %}
  {% for post in sorted_posts %}
    <li>
      <a href="{{ post.url }}" class="dark-link">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
![Alt text](/assets/images/robot.jpeg)

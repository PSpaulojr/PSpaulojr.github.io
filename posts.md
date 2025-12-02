---
layout: default
title: "All Posts"
permalink: /posts/
---
<div style="width: 100%; text-align: right; margin-bottom: 1rem;">
  <a href="{{ '/' | relative_url }}">Home</a> |
  <a href="{{ '/about/' | relative_url }}">About</a> |
  <a href="{{ '/posts/' | relative_url }}">Posts</a>
</div>

# All Posts

Here is a list of all my posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

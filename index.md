---
layout: default
title: "Home"
---
<div style="width: 100%; text-align: right; margin-bottom: 1rem;">
  <a href="{{ '/' | relative_url }}">Home</a> |
  <a href="{{ '/about/' | relative_url }}">About</a> |
  <a href="{{ '/posts/' | relative_url }}">Posts</a>
</div>

# Welcome to my blog!

I am a data engineer with a background in Electrical Engineering (FEEC/UNICAMP). I am an enthusiastic programmer, passionate about machine learning and problem-solving. Here, I share article reviews, book summaries, and my technical progress in machine learning.

## Last Posts

{% for post in site.posts  %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
---

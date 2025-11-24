---
layout: default
title: "Home"
---

# 👋 Welcome to my blog!

I am a data engineer. Here I share article reviews, book summaries, as well as my technical progress

## 📝 Últimos Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
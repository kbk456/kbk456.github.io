---
layout: default
title: Study Log
permalink: /study/
---

# Study Log

개발하면서 배운 것들을 기록합니다.

---

{% for post in site.posts %}
- **{{ post.date | date: "%Y-%m-%d" }}** — [{{ post.title }}]({{ post.url }})
{% endfor %}

{% if site.posts.size == 0 %}
글이 아직 없습니다. 곧 업데이트됩니다.
{% endif %}

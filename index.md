---
layout: default
title: Home
---

# 공부 블로그

매일 배운 것을 기록합니다.

---

## 최근 글

{% for post in site.posts limit:10 %}
- **{{ post.date | date: "%Y-%m-%d" }}** - [{{ post.title }}]({{ post.url }})
{% endfor %}

---

## 카테고리

다양한 주제의 공부 내용을 정리합니다.

---
sidebar:
  nav: "docs"
permalink: /:title
title: "모던 자바스크립트 입문"
author: 이정배
---

모던 자바스크립트 입문을 공부한 내용을 정리해 두는 문서입니다.

## 목차

{% for item in site.modern-javascript %}
### [{{item.title}}]({{item.url}}) {% if item.author != null %} by {{item.author}} {% endif %}
{% endfor %}

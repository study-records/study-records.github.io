---
sidebar:
  nav: "docs"
permalink: /:title
title: "Kubernetes 스터디"
author: 이정배
---

Kubernetes 공부한 내용을 정리해 두는 문서입니다.

## 목차

{% for item in site.kubernetes %}
### [{{item.title}}]({{item.url}}) {% if item.author != null %} by {{item.author}} {% endif %}
{% endfor %}

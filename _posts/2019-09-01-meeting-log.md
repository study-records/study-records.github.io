---
sidebar:
  nav: "docs"
permalink: /:title
title: "회의록"
author: 이정배
---

모임을 진행하며 회의한 내용을 을 정리해 두는 문서입니다.

## 목차

{% for item in site.meeting-log %}
### [{{item.title}}]({{item.url}}) {% if item.author != null %} by {{item.author}} {% endif %}
{% endfor %}

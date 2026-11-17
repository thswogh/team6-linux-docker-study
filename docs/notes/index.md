---
title: 학습 정리 글 목록
---

# 학습 정리 글 목록

각자 `docs/notes/내영문이름/` 폴더에 올린 글이 자동으로 아래에 나타나요.

{% assign notes = site.pages | where_exp: "p", "p.path contains 'notes/'" | where_exp: "p", "p.name != 'index.md'" | sort: "path" %}
{% for n in notes %}
- [{{ n.title | default: n.name }}]({{ n.url | relative_url }}) · {{ n.author }} · {{ n.date }}
{% endfor %}

---
title: Articles
layout: single
permalink: /articles/
#collection: articles
entries_layout: grid
classes: wide
---
| title  | excerpt |
| ----- | -------- |{% for article in site.articles %}
|[{::nomarkdown}{{article.title }}{:/}]({{article.url}})|{::nomarkdown}{{article.excerpt }}{:/}|{% endfor %}

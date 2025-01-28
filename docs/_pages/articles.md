---
title: Articles
layout: single
permalink: /articles/
#collection: articles
entries_layout: grid
classes: wide
---
| Title  | Excerpt |
| ----- | -------- |{% for article in site.articles %}
|[{::nomarkdown}A {{article.Title }}{:/}]({{article.url}})|{::nomarkdown}{{article.Excerpt }}{:/}|{% endfor %}

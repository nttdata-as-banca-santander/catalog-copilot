---
layout: splash
title: "Inicio"
---

{% assign items = site.prompts %}

{% include cards-grid.html
items=items
title_field="title"
info_field="excerpt"
url_field="url"
tag_field="tags"
%}
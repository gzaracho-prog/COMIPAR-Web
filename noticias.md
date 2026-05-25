---
layout: page
title: Noticias
permalink: /noticias/
---

## Actualidad de COMIPAR

Sigue aquí las noticias, comunicados y novedades relacionadas con la migración paraguaya y las actividades de COMIPAR.

---

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url | relative_url }})

**{{ post.date | date: "%d/%m/%Y" }}**

{{ post.excerpt }}

[Leer noticia completa →]({{ post.url | relative_url }})

---

{% endfor %}

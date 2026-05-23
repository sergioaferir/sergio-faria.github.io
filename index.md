# The Digital Operator

> Transformar desorganização em controlo.

[Home](/) | [Sobre](/about)

---

Sistemas, organização e cibersegurança no mundo real.

---

## ✍️ Artigos


{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
<small>{{ post.date | date: "%d/%m/%Y" }}</small>

---
{% endfor %}

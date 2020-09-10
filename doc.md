---
title: Other documents
root: ..
permalink: /docs/
---
{% for p in site.doc %}
* [{{ p.title }}]({% include link.html url=p.url %})
{% endfor %}

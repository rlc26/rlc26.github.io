---
layout: default
title: "Danse Latine"
---

# {{ page.title }}

{{ site.description }}

{% for dance in site.dance_styles %}
## {{ dance.name }}
**Origine** : {{ dance.origin }}  
**Description** : {{ dance.description }}
{% endfor %}

[View My GitHub Profile](https://github.com/rlc26)

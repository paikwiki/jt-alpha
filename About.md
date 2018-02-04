---
layout: page
title: About
permalink: /about
---

{{ site.data.author.description }}

- {{ site.data.author.email }}

# Exhibitions

{% for exgroup in site.data.author.exhibitions %}

## {{ exgroup.title }}

{% for exitem in exgroup.list %}

- {{ exitem }}

{% endfor %}

{% endfor %}
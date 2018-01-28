---
layout: page
title: About
permalink: /about
---

I draw a cat and a dog.

- email: {{ site.data.author.email }}

# Exhibitions

{% for exgroup in site.data.author.exhibitions %}

## {{ exgroup.title }}

{% for exitem in exgroup.list %}

- {{ exitem }}

{% endfor %}

{% endfor %}
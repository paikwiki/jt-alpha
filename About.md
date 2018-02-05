---
layout: page
title: About
permalink: /about
---

{{ site.data.author.description }}

- <a href="mailto://{{ site.data.author.email }}">{{ site.data.author.email }}</a>

# Exhibitions

{% for exgroup in site.data.author.exhibitions %}

## {{ exgroup.title }}

{% for exitem in exgroup.list %}

- {{ exitem }}

{% endfor %}

{% endfor %}
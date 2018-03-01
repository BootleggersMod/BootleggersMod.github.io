---
layout: page
title: Downloads & Source
{% assign devices = "surnia,mido,kenzo,land,lettuce" | split: ',' %}
{% assign maintainers = "ElDainosor,merothh,dinosnore,taran105,Nikhil" | split: ',' %}
---

{% for devcode in devices %}
{{ devcode }}
{% endfor %}

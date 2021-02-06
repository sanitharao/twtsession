---
layout: template_file
title: Rising Sun

---

# {{ page.title }}

# New File for Demo

This is a new file that will be linked from the Index file.

show the name {{ site.name }}

show the time: {{ site.when }}

Data File contents:

{% for item in site.data.demo %}

The country of {{ item.name }} was created in {{ item.date }} and its flag is {{ item.flag }}

{% endfor %}

{% include common2.txt %}

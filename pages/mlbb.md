---
layout: page
title: MLBB Pricing
permalink: /mlbb/
---


| Pack | Cost | Selling Price (Profit) |
| :--- | :--- | :--- |
{% for pack in site.data.dias %}
| **{{ pack.diamonds }}** | {{ pack.cost }} | {% for item in pack.profits %}₱{{ item.target }} ({{ item.value }})<br>{% endfor %} |
{% endfor %}

---
layout: page
title: MLBB Pricing
permalink: /mlbb/
---

| MLBB Diamond Pricing & Profit |
| :--- |
{% for pack in site.data.dias %}
| **{{ pack.diamonds }}**<br>• Cost (Base+VAT): {{ pack.cost }}<br>{% for profit in pack.profits %}• Profit at near {{ profit.target }}: {{ profit.value }}<br>{% endfor %} |
{% endfor %}

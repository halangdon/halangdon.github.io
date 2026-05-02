---
layout: page
title: MLBB Pricing
permalink: /mlbb/
---

| MLBB Diamond Pricing & Profit |
| :--- |
{% for pack in site.data.dias %}
| **{{ pack[1] }}**<br>• {{ pack[2] | replace: ":", ": " }}<br>{% for entry in pack offset:3 %}• {{ entry[0] | capitalize }}: {{ entry[1] }}<br>{% endfor %} |
{% endfor %}

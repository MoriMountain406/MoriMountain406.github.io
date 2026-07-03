---
title: Debug Haskaps Data
layout: page
permalink: /atlas/species/Haskaps/debug/
---

# Data Test

{% for c in site.data.haskaps.cultivars %}
- {{ c.name }} ({{ c.role }})
{% endfor %}

---
layout: default
title: PECS 2024 - 4th International Workshop on Performance and Energy Efficiency in Concurrent and Distributed Systems
---

{% include banner.html picture="concurrent.png" %}<!-- @IGNORE PREVIOUS: link -->

---

{% for coll in site.collections %}{% if coll.label == page.collection %}{% assign edition = coll %}{% endif %}{% endfor %}
{%- assign year = page.collection -%}

The {{edition.description}} ({{site.title}} {{ year }}) will take place on {{ edition.dates }}. The workshop will be co-located with the [33rd International Symposium on High-Performance Parallel and Distributed Computing (HPDC 2024)](https://www.hpdc.org/2024/).

PECS aims to establish a venue for both academia and industry to discuss challenges and perspectives, and to explore methods, techniques and tools for energy efficiency and performance optimization in concurrent and distributed systems.

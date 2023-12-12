---
layout: default
title: PECS 2023 - Workshop on Performance and Energy Efficiency in Concurrent and Distributed Systems
---

{% include banner.html picture="concurrent.png" %}<!-- @IGNORE PREVIOUS: link -->

---

{% for coll in site.collections %}{% if coll.label == page.collection %}{% assign edition = coll %}{% endif %}{% endfor %}
{%- assign year = page.collection -%}

The {{ year }} {{edition.description}} ({{site.title}} {{ year }}) will take place on {{ edition.dates }}. The workshop will be co-located with the [ 29th International European Conference on Parallel and Distributed Computing (Euro-Par 2023)](https://2023.euro-par.org/).

PECS aims to establish a venue for both academia and industry to discuss challenges and perspectives, and to explore methods, techniques and tools for energy efficiency and performance optimization in concurrent and distributed systems.

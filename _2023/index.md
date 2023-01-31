---
layout: default
title: "Workshop on Performance and Energy-efficiency in Concurrent Systems"
---

{% include banner.html picture="concurrent.png" %}<!-- @IGNORE PREVIOUS: link -->

---

{% for coll in site.collections %}{% if coll.label == page.collection %}{% assign edition = coll %}{% endif %}{% endfor %}
{%- assign year = page.collection -%}

The {{ year }} {{site.description}} ({{site.title}} {{ year }}) will take place on {{ edition.dates }}. The workshop will be co-located with the [ 29th International European Conference on Parallel
and Distributed Computing](https://2023.euro-par.org/).

{% include_relative _introduction_text.md %}





## Important Dates

{% include_relative _important_dates.md %}

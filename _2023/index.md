---
layout: default
title: "Workshop on Performance and Energy-efficiency in Concurrent Systems"
---

{% include banner.html picture="concurrent.png" %}<!-- @IGNORE PREVIOUS: link -->

---

{% for coll in site.collections %}{% if coll.label == page.collection %}{% assign edition = coll %}{% endif %}{% endfor %}
{%- assign year = page.collection -%}

The {{ year }} {{site.description}} ({{site.title}}) will take place on {{ edition.dates }}. The workshop will be co-located with the [ 29th International European Conference on Parallel
and Distributed Computing](https://2023.euro-par.org/).

Concurrent and distributed computer architectures, based on multi/many-core or distributed computer units, have become a standard de-facto in computer systems. Today, these architectures take a role at any scale, from high-end servers to personal and mobile devices, and they underlie various recent computing paradigms, like Cloud, Edge and Fog Computing.

The continuously-growing level of hardware parallelism and heterogeneity has led concurrent and distributed systems to be even more complex to optimize, in particular in terms of energy efficiency and performance, which are known to be highly interrelated. Nonetheless, these aspects are of paramount importance, especially because of the IT sector’s high demand for electricity. This facet is further exacerbated by the recent energy crisis and rising energy prices.

Several aspects of concurrent and/or distributed systems make highly challenging the improvement of both energy efficiency and performance levels, like the complexity of the underlying architectures, data dependencies, the use of shared resources, the hardware heterogeneity. On the other hand, all these aspects can offer new opportunities for identifying and designing new methods and techniques for energy and performance optimization.
PECS aims to establish a venue for both academia and industry to discuss challenges and perspectives, and to explore opportunities, research methods, techniques and tools for energy efficiency and performance optimization in concurrent and distributed systems.





## Important Dates

{% include_relative _important_dates.md %}

---
layout: default
title: "PECS 2021 - 1st International Workshop on Performance and Energy Efficiency in Concurrent Systems"
---

{% include banner.html picture="concurrent.png" %}<!-- @IGNORE PREVIOUS: link -->

---

{% for coll in site.collections %}{% if coll.label == page.collection %}{% assign edition = coll %}{% endif %}{% endfor %}
{%- assign year = page.collection -%}

The {{ year }} {{site.description}} ({{site.title}}) will take place at {{ edition.location }} on {{ edition.dates }} in {{ edition.venue }}. The workshop will be co-located with the [12th ACM/SPEC International Conference on Performance Engineering](https://icpe2021.spec.org/).

Concurrent systems, based on (distributed) multi/many-core processing units, are the nowadays reference computing architecture. The (continuously-growing) level of hardware parallelism they offer has lead these platforms to play a central role at any scale, ranging from data centers, to personal (mobile) devices. Optimizing performance and/or ensuring energy efficiency when running complex software stacks on top of these systems is extremely challenging due to several aspects, like data dependencies or resource sharing (and interference) among application threads, as well as VMs. Furthermore, hardware accelerators like GPGPUs or FPGAs introduce a level of heterogeneity that can potentially offer further opportunities for combined gain in performance and energy efficiency, if correctly exploited.

The goal of this workshop is to establish a venue for both academia and industry experts and practitioners, where they can discuss challenges, perspectives and opportunities given by researching on scalable, energy-efficient and secure software deployed on top of modern (heterogeneous) concurrent platforms.

## Current organization status

At current time, due to the uncertainty around the COVID pandemic, we cannot guarantee it will be possible to have a physical workshop. We also recognize the challenges some of our community members might face in traveling. According to the main ICPE conference, the conference model is "on-site with remote participation facilities", meaning that the organizing committee is looking forward to a live event, but will provide the required infrastructure for online presence.

## Important Deadlines

{% include_relative _important_dates.md %}

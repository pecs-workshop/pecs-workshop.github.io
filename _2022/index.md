---
layout: default
title: "PRCS 2022 - 2nd Workshop on Performance and Energy Efficiency in Concurrent Systems"
---

{% include banner.html picture="concurrent.png" %}<!-- @IGNORE PREVIOUS: link -->

---

{% for coll in site.collections %}{% if coll.label == page.collection %}{% assign edition = coll %}{% endif %}{% endfor %}
{%- assign year = page.collection -%}

The {{site.description}} ({{site.title}}) will take place as a **{{ edition.location }}** on {{ edition.dates }}. The workshop will be co-located with the [ACM International Symposium on High-Performance, Parallel and Distributed Computing (HPDC)](https://www.hpdc.org/2024/).

Concurrent systems, based on (distributed) multi/many-core processing units, are the nowadays reference computing architecture. The (continuously-growing) level of hardware parallelism they offer has lead these platforms to play a central role at any scale, ranging from data centers, to personal (mobile) devices. Optimizing performance and/or ensuring energy efficiency when running complex software stacks on top of these systems is extremely challenging due to several aspects, like data dependencies or resource sharing (and interference) among application threads, as well as VMs. Furthermore, hardware accelerators like GPGPUs or FPGAs introduce a level of heterogeneity that can potentially offer further opportunities for combined gain in performance and energy efficiency, if correctly exploited.

The goal of this workshop is to establish a venue for both academia and industry experts and practitioners, where they can discuss challenges, perspectives and opportunities given by researching on scalable, energy-efficient and secure software deployed on top of modern (heterogeneous) concurrent platforms.

## Virtual Event

Given the uncertainty around the COVID pandemic, and also considering the success and the positive feedback of the previous edition, the {{ year }} {{site.description}} ({{site.title}}) will take place as a **virtual event**. We also consider this as an opportunity to foster a broader participation in the workshop.

## Important Deadlines

{% include_relative _important_dates.md %}

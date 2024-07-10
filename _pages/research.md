---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

Dr. Neal leads the Cyber Identity and Behavior Research (CIBeR) Lab. Our research is inspired by the pervasive nature of today's technologies and how smart sensing, enabled by these technologies, can be used to understand human interactions with technology, interpersonal interactions, and behaviors in various environments. We primarily use applied artificial intelligence and human-centered computing techniques to explore:

- Usable and inclusive cybersecurity systems for personally-owned computing devices, with a particular focus on identity and access management
- Interdisciplinary applications of human behavior analysis through smart sensing

{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

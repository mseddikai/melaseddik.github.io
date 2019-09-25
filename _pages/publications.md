---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**From Outage Probability to ALOHA MAC Layer Performance Analysis in Distributed WSNs**,
MEA.Seddik, V.Toldov, L.Clavier, N.Mitton, WCNC'2018 [[paper](https://hal.inria.fr/hal-01677687/document)]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

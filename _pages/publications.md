---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
* Zhedong Ma, Juntao Yao, Yiming Li and Shuo Wang: Comparative Analysis of Magnetic Core Loss Measurement Methods with Arbitrary Excitations. IEEE Energy Conversion Congress and Exposition 2019.

* Juntao Yao, Mohammed El-Sharkh, Yiming Li, Zhedong Ma, Shuo Wang and Zheng Luo：Investigation of Radiated EMI in Non-isolated Power Converters with Power Cables in Automotive Applications. IEEE Energy Conversion Congress and Exposition 2019.

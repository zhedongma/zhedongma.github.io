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
* Z. Ma, J. Yao, Y. Li and S. Wang, "Comparative Analysis of Magnetic Core Loss Measurement Methods with Arbitrary Excitations," 2019 IEEE Energy Conversion Congress and Exposition (ECCE), Baltimore, MD, USA, 2019, pp. 4125-4130.

* J. Yao, M. El-Sharkh, Y. Li, Z. Ma, S. Wang and Z. Luo, "Investigation of Radiated EMI in Non-isolated Power Converters with Power Cables in Automotive Applications," 2019 IEEE Energy Conversion Congress and Exposition (ECCE), Baltimore, MD, USA, 2019, pp. 6957-6964.

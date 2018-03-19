---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my full list of publications on [my Google Scholar profile](https://scholar.google.com/citations?user=95oJGacAAAAJ&hl=en&oi=ao).

Finn ES et al. "Functional connectome fingerprinting: identifying individuals using patterns of brain connectivity." [[pdf]](https://esfinn.github.io/files/nn.4135.pdf)

Finn ES et al. "Can we manipulate brain state to emphasize individual differences in functional connectivity?" [[pdf]](https://esfinn.github.io/files/nn.4135.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

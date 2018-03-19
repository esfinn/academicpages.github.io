---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my full list of publications on [[my Google Scholar profile]](https://scholar.google.com/citations?user=95oJGacAAAAJ&hl=en&oi=ao).

### Selected publications

**Finn ES**, Scheinost D, Finn DM, Shen X, Papademetris X, Constable RT. "Can we manipulate brain state to emphasize individual differences in functional connectivity?" [[pdf]](https://esfinn.github.io/files/nn.4135.pdf)

**Finn ES**, Shen X, Scheinost D, Rosenberg MD, Huang J, Chun MM, Papademetris X, Constable RT. "Functional connectome fingerprinting: identifying individuals using patterns of brain connectivity." [[pdf]](https://esfinn.github.io/files/nn.4135.pdf)[[code]](https://www.nitrc.org/frs/?group_id=51)

### Other publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

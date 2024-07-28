---
layout: archive
title: "Publications"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


# On-going Projects
1. Robust Continual Federted Learning Under Byzantine Attacks
2. Bayesian Federated Continual Learning with Overlapped Task Boundaries
3. A Generalized Approach to Continual Learning Beyond Model Architectures
<!-- 3. Continual Learning Beyond Model Architecture: A Generalization Approach  -->

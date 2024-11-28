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

### On-going Works
1. Bayesian Federated Continual Learning with Overlapped Task Boundaries
2. Continual Learning All at Once: Multi-task Continual Learning Using Credal Learning Theory.
3. Robust Continual Federted Learning Under Byzantine Attacks. 
<!-- 3. A Generalized Approach to Continual Learning Beyond Model Architectures. -->
<!-- 3. Continual Learning Beyond Model Architectures: A Generalization Approach  -->


<!-- ### Thesis and Project Reports:
1. Summer Research Thesis on Computer Vision at ECSU, ISI Kolkata. <a href="../files/Image_dehazing_report.pdf" target="_blank">[pdf]</a>
2. Masters Thesis. <a href="../files/Satish_MS_Thesis.pdf" target="_blank">[pdf]</a>
3. Report on Comparison between Different second-orer optimization algorithms.<a href="../files/Satish_MS_Thesis.pdf" target="_blank">[pdf]</a> -->

<!-- <embed src="../files/Image_dehazing_report.pdf" type="application/pdf" frameBorder="0" scrolling="auto" height="100%"
  width="100%"></embed> -->



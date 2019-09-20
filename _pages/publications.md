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


* Feng, Rui, Yang Yang, Wenjie Hu, Fei Wu, and Yueting Zhang. "<a href="https://arxiv.org/abs/1711.10755">Representation learning for scale-free networks</a>" In <i> Thirty-Second AAAI Conference on Artificial Intelligence</i>. 2018.
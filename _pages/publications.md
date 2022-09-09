---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<b>RAScatter: Achieving Energy-Efficient Backscatter Readers via AI-Assisted Power Adaptation</b> <br>
<b>Kai Huang</b>, Ruirong Chen, Wei Gao <br>
<i>2022 IEEE/ACM Seventh International Conference on Internet-of-Things Design and Implementation (IoTDI) (<b>IEEE IoTDI 2022</b>)<br>
<i>[[PDF]](https://ieeexplore.ieee.org/document/9797444)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Content Delivery
======

*Ting Liu, Tianhao Miao, Qinghua Wu, Zhenyu Li, Guangxin He, Jiaoren Wu, Xingwu Yang, Gareth Tyson and Gaogang Xie. Demystifying Scaling Performance Bottlenecks in Distributed Deep Learning. In 31st ACM Web Conference (WWW), Lyon, France (2022)

Content Delivery
======

Content Delivery
======


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

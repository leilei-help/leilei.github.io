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

-title: "Multi-objective shape optimization of autonomous underwater glider based on fast elitist non-dominated sorting genetic algorithm"
-journal: Ocean Engineering
-author: FU Xiao-Yun, Lei Lei, Yang Gang, Li Bao-Ren
-year: 2018

-title: "Wing parameter configuration and steady motion analysis of water-jet hybrid glider"
-journal: Journal of Zhejiang University
-author: FU Xiao-Yun, Lei Lei, Yang Gang, Li Bao-Ren
-year: 2018

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



1. Jeonghyun Kim, Kevin Montagne, Takashi Ushida, Katsuko S Furukawa* (2015). Enhanced chondrogenesis with upregulation of PKR using a novel hydrostatic pressure bioreactor, Bioscience, Biotechnology, and Biochemistry. 79:2, 239-241.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

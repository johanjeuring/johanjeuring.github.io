---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my articles on <u><a href="https://scholar.google.com/citations?user=weRJxNwAAAAJ">Google Scholar</a></u>, 
<u><a href="https://dblp.org/pid/j/JohanJeuring.html">DBLP</a></u>, and
<u><a href="https://dl.acm.org/profile/81100339289)">ACM DL</a></u>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

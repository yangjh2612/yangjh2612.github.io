---
layout: archive
title: "Publications"
permalink: #/publications/
author_profile: true
---



Check

I am an applied economist with strong interests in interdisciplinary work. My research has focused on information-theoretic approaches in economics, power-law behaviour in economic data, and Bayesian multilevel modelling. I have published in economics and multidisciplinary science journals such as [Journal of Evolutionary Economics](https://www.springer.com/journal/191), [International Review of Financial Analysis](https://www.sciencedirect.com/journal/international-review-of-financial-analysis), [Metroeconomica](https://onlinelibrary.wiley.com/journal/1467999x), [Journal of Economic Surveys](https://onlinelibrary.wiley.com/journal/14676419), [Economics Systems Research](https://www.tandfonline.com/toc/cesr20/current), [Entropy](https://www.mdpi.com/journal/entropy), [European Physical Journals Special Topics](https://www.springer.com/journal/11734), and [Advances in Complex Systems](https://www.worldscientific.com/worldscinet/acs).


Contact
------
Mailing address: University of Waterloo, Department of Management Sciences, 200 University Avenue West, Waterloo, ON   N2L 3G1, CANADA

E-mail: j634yang[at]uwaterloo.ca



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

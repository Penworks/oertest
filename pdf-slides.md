---
title: PDF Slides
layout: page
---



<!-- [link](some.pdf) -->
<!-- <object data="assets/slides/changing-purposes-_-priorities-for-higher-education.pdf" width="1000" height="1000" type='application/pdf'></object> -->


## All posts in chronological order
<nav>
  <ul id="secondary-nav">
{% for p in site.posts %}
 <li>{{ p.date | date_to_string }} &nbsp; <a href="{{ p.url | relative_url }}">{{ p.title }}</a></li>
{% endfor %}

</ul>
</nav>
---
layout: page
title: Μάθε τώρα
permalink: /learn.now/

---
 
<ul>
  {% for p in site.pois %}
    <li>
      <a href="{{ p.url | relative_url}}">{{ p.title }}</a>
    </li>
  {% endfor %}
</ul>

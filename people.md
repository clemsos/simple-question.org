---
title: "L'Equipe"
layout: page
---

<ul id="team">
{% for people in site.data.team.members %}
  <li>
    {% include headshot.html people=people %}
  </li>
{% endfor %}
</ul>

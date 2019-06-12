---
layout: default

---

<ul>
{% for monument in site.data.monuments %}
  <li>
    <a href="http://proposals.monumentlab.com/monuments/{{ monument.id }}">
      {{ monument.title }}
    </a>
  </li>
{% endfor %}
</ul>

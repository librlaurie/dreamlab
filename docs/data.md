---
layout: default

---

<ul>
{% for monument in site.data.monuments %}
  <li>
    <a href="http://proposals.monumentlab.com/monuments/{{ monument.pid }}">
      {{ monument.title }}
    </a>
    <p>This proposal is from {{ monument.neighborhood }}. That means the person who proposed it was from that zipcode. It was made by {{ monument.credit }}. They are from {{ monument.age_range }} years old.</p>
  </li>
{% endfor %}
</ul>

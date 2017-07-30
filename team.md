---
layout: page
order: 1
title: Team
permalink: /team/
---

<div class="card-container">
{% for person in site.data.team %}
  <div class="person-card">
    <div class="person-card-image-container">
      <img src="{{ site.baseurl }}/images/{{ person.image }}" />
    </div>
    <div class="person-card-text-container">
      <h3>{{ person.name }}</h3>
      <h4>{{ person.role }}</h4>
      <p>{{ person.bio }}</p>
    </div>
  </div>
{% endfor %}
</div>

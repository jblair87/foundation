---
layout: default
order: 1
title: Team
permalink: /team/
---

<h1>The Oppia Foundation Team</h1>
<h2>Oppia is powered by volunteers from across the globe.</h2>
<p>Our diverse, open source community includes educators, students, software engineers, designers, and others who all share our passion for improving education. Contributors to Oppia have worked for leading companies like Google, Quora, and Codecademy, and they've attended renowned institutions like Carnegie Mellon, Georgia Tech, and the University of Cambridge.</p>

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

<div class="person-card">
  <div class="person-card-image-container">
    <img src="{{ site.baseurl }}/images/{{ person.image }}" />
  </div>
  <div class="person-card-text-container">
    <h3>You?</h3>
    <h4>clever clever headline</h4>
    <p>copy that makes the person want to click to the next page</p>
  </div>
</div>

</div>

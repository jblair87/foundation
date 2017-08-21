---
layout: default
---

<h1>Over 250 million children around the world don't get the education they deserve.</h1><h1>Together, we can help fix that.</h1>

<div id="icons">
  <a href="{{ site.baseurl }}/mission">
    <div class="icon-holder">
      <div class="icon-background">
        <img src="{{ site.baseurl }}/images/icon-mission.png" />
      </div>
      <div class="icons-text-container">
        <p>Oppia exists to improve educational outcomes for learners around the world.</p>
      </div>
      <div class="icons-cta-container">
        <p>Read Oppia's Mission <i class="material-icons">&#xE5C8;</i></p>
      </div>
    </div>
  </a>
  <a href="{{ site.baseurl }}/team">
    <div class="icon-holder">
      <div class="icon-background">
        <img src="{{ site.baseurl }}/images/icon-team.png" />
      </div>
      <div class="icons-text-container">
        <p>Our diverse, world-class team cares deeply about improving education.</p>
      </div>
      <div class="icons-cta-container">
        <p>Meet the Oppia Team <i class="material-icons">&#xE5C8;</i></p>
      </div>
    </div>
  </a>
  <a href="{{ site.baseurl }}/get-involved">
    <div class="icon-holder">
      <div class="icon-background">
        <img src="{{ site.baseurl }}/images/icon-get-involved.png" />
      </div>
      <div class="icons-text-container">
        <p>Hundreds of people around the world have contributed to Oppia.</p>
      </div>
      <div class="icons-cta-container">
        <p>Help Us Help Learners <i class="material-icons">&#xE5C8;</i></p>
      </div>
    </div>
  </a>
</div>

<div id="press">
  <p>As seen in</p>
  {% for logo in site.data.press %}
    <a href="{{ logo.link }}"><img src="{{ site.baseurl }}/images/{{ logo.image }}" style="height: {{ logo.height }}px; margin-top: {{ logo.margin_top }}px" /></a>
  {% endfor %}
</div>

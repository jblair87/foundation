---
layout: default
---

<h1>250 million children lack basic literacy and numeracy. Together, we can help fix that.</h1>

<div id="icons">
  <a href="#">
    <div class="icon-holder">
      <div class="icon-background">
        <img src="{{ site.baseurl }}/images/icon-mission.png" />
      </div>
      <div class="icons-text-container">
        <p>something about oppia's mission</p>
      </div>
      <div class="icons-cta-container">
        <p>Read Oppia's Mission</p>
        <i class="material-icons">&#xE5C8;</i>
      </div>
    </div>
  </a>
  <a href="#">
    <div class="icon-holder">
      <div class="icon-background">
        <img src="{{ site.baseurl }}/images/icon-team.png" />
      </div>
      <div class="icons-text-container">
        <p>something about oppia's team</p>
      </div>
      <div class="icons-cta-container">
        <p>Meet the Oppia Team</p>
        <i class="material-icons">&#xE5C8;</i>
      </div>
    </div>
  </a>
  <a href="#">
    <div class="icon-holder">
      <div class="icon-background">
        <img src="{{ site.baseurl }}/images/icon-get-involved.png" />
      </div>
      <div class="icons-text-container">
        <p>something about getting involved</p>
      </div>
      <div class="icons-cta-container">
        <p>Help Us Help Learners</p>
        <i class="material-icons">&#xE5C8;</i>
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

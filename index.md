---
layout: default
---

<h1>250 million children lack basic literacy and numeracy. Together, we can help fix that.</h1>

<div id="press">
  <p>As seen in</p>
  {% for logo in site.data.press %}
    <a href="{{ logo.link }}"><img src="{{ site.baseurl }}/images/{{ logo.image }}" style="height: {{ logo.height }}px; margin-top: {{ logo.margin_top }}px" /></a>
  {% endfor %}
</div>

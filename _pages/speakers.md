---
layout: page
title: Speakers
permalink: /speakers/
order: 2
onFrontPage: true
---

## Speakers

<div class="speakers">

JOLALALA

<ul class="gallery">
{% for talk in site.data.talks %}
  {% for speaker in talk.speakers %}
  <li class="gallery-item">
    <a href="{{ speaker.twitter_link }}" target="_blank">
      <img src="{{ site.path }}/assets/img/{{ speaker.image}}" alt="{{speaker.name}}" />
    </a>
    <h3>{{speaker.name}}</h3>
  </li>  
  {% endfor %}
{% endfor %}
</ul>

</div>

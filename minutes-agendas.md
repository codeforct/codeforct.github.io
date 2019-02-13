---
layout: page
title: Steering Committee Meeting Minutes and Agendas
use-site-title: true
---

<p>Here you will find agendas and minutes from Steering Committe meetings.</p>
<p>Agendas will be posted 4 days prior to a steering committee meeting and minutes will be posted within 2 days following the meeting, per our <a href="../bylaws">bylaws</a>.</p>

{% for ma in site.minutes-agendas reversed %}
  <h2>
    <a href="{{ ma.url | prepend:site.baseurl }}">
      {{ ma.title }}
    </a>
  </h2>
{% endfor %}
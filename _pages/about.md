---
permalink: /
title: "Atefeh Mollabagher"
excerpt: "ECE Ph.D. student at UC San Diego"
toc: false
---

Hi! I am **Atefeh Mollabagher**, a Ph.D. student in Electrical and Computer Engineering at
[UC San Diego](https://ucsd.edu), advised by
[Dr. Parinaz Naghizadeh](https://parinazn.com).
Before that, I received my B.Sc. in Electrical Engineering from the
[University of Tehran](https://ece.ut.ac.ir/en).
My research focuses on recommender systems, multi agent reinforcement learning, and opinion dynamics.

✉️ atefeh@ucsd.edu



## Publications

{% assign recent = site.publications | sort: 'date' | reverse | slice: 0, 2 %}
<div class="pubs-compact">
{% for p in recent %}
  <div class="pub">
    <div class="title"><a href="{{ p.url | relative_url }}">{{ p.title }}</a></div>
    <div class="meta">
      {{ p.authors }} · <em>{{ p.venue }}</em>{% if p.date %}, {{ p.date | date: "%Y" }}{% endif %}
      {% if p.paperurl %} · <a href="{{ p.paperurl }}">PDF</a>{% endif %}
    </div>
  </div>
{% endfor %}
</div>

<p><a href="{{ '/publications/' | relative_url }}">See all →</a></p>


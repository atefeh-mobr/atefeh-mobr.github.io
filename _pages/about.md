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

## Ongoing projects

- **Multi-Agent RL for Recommender–User Interaction.** Building a framework where both RS and users are adaptive agents; studying drift, fairness–accuracy trade-offs, and platform interventions.
- **Recommendation–User Feedback Loops.** Modeling closed-loop dynamics and mitigation policies (deterministic + stochastic) with convergence and robustness analysis.

## Teaching

- **TA, ECE 250 – Probability & Random Processes (Fall 2025), UC San Diego.** Led discussions, rubrics, and grading.
- **TA, ECE 153 – Probability & Random Processes for Engineers (Spring 2025).** Led discussions, rubrics, and grading.

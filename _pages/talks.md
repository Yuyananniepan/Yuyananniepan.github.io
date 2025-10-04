---
layout: page
title: "Talks and Presentations"
permalink: /talks/
---

<style>
.talk-entry {
  margin-bottom: 2rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid #e0e0e0;
}
.talk-title {
  font-size: 1.2rem;
  font-weight: bold;
  color: #2c3e50;
}
.talk-event {
  font-size: 1rem;
  font-weight: 500;
  color: #34495e;
}
.talk-meta {
  font-size: 0.9rem;
  color: #7f8c8d;
}
</style>

{% for talk in site.data.talks %}
<div class="talk-entry">
  <div class="talk-title">{{ talk.title }}</div>
  <div class="talk-event">{{ talk.event }}</div>
  <div class="talk-meta">{{ talk.location }} | {{ talk.date }}</div>
</div>
{% endfor %}


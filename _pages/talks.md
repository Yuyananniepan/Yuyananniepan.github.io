---
layout: page
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

<style>
.talks-content {
  padding-left: 2rem;
  padding-right: 2rem;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.talk-entry {
  margin-bottom: 2rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid #ddd;
}

.talk-title {
  font-weight: bold;
  font-size: 1.1rem;
  color: #2c3e50;
}

.talk-event {
  font-weight: 500;
  font-size: 1rem;
  color: #555;
}

.talk-meta {
  font-size: 0.9rem;
  color: #888;
}
</style>

<div class="talks-content">
  {% for talk in site.data.talks %}
    <div class="talk-entry">
      <div class="talk-title">{{ talk.title }}</div>
      <div class="talk-event">{{ talk.event }}</div>
      <div class="talk-meta">{{ talk.location }} | {{ talk.date }}</div>
    </div>
  {% endfor %}
</div>

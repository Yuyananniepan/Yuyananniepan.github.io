---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

## Academic Presentations

{% for talk in site.data.talks %}
- **{{ talk.title }}**  
  {{ talk.event }}, {{ talk.location }}, {{ talk.date }}
{% endfor %}

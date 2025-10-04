---
layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

{% for talk in site.data.talks %}
- **{{ talk.title }}**  
  *{{ talk.event }}*  
  {{ talk.location }} | {{ talk.date }}

{% endfor %}


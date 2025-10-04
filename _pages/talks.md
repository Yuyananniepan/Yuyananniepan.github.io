---
layout: page
title: "Talks and Presentations"
permalink: /talks/
---

{% for talk in site.data.talks %}
### {{ talk.title }}
**{{ talk.event }}**  
{{ talk.location }}  
{{ talk.date }}

<br>
{% endfor %}

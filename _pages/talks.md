---
layout: archive
title: "Talks and Presentations"
permalink: /talks/
author_profile: true
---

{%- assign groups = site.data.talks | group_by: "year" | sort: "name" | reverse -%}

{%- for g in groups -%}
### {{ g.name }}
{%- assign items = g.items | sort: "month_num" | reverse -%}
{%- for talk in items -%}
- **{{ talk.title }}**  
  *{{ talk.event }}*  
  {{ talk.location }} | {{ talk.date }}
{%- endfor -%}

{%- endfor -%}

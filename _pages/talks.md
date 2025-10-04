{% for talk in site.data.talks %}
- **{{ talk.title }}**
  {{ talk.event }}, {{ talk.location }}, {{ talk.date }}
{% endfor %}

---
layout: default
title: Projects
---

# Projects

Soon.

<hr>

{% assign postsByYear = site.projects | group_by_exp: "project", "project.date | date: '%Y'" %}
{% for year in postsByYear %}
  <h2>{{ year.name }}</h2>
  <ul>
    {% for post in year.items %}
   <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
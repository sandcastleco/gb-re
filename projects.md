---
layout: default
title: Projects
permalink: /projects
---

# Projects

Current development sites are listed below. Please Click on the links below to learn more about the specific projects and the opportunities that are available.

{% for project in site.data.projects %}
  <hr>
  <div class="row">
    <div class="card">
      <div class="col-sm-4">
        <a href="{{ project.link }}"><img src="/images/{{ project.image }}"></a>
      </div>
      <div class="col-sm-8">
        <h2><a href="{{ project.link }}">{{ project.name }}</a></h2>
        <p>{{ project.description }}</p>
      </div>
    </div>
  </div>
{% endfor %}

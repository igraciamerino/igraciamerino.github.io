---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Journal Publications

{% for post in site.publications reversed %}
  {% if post.category == "journal" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Conference Publications

{% for post in site.publications reversed %}
  {% if post.category == "conference" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Manuscripts Under Review

{% for post in site.publications reversed %}
  {% if post.category == "under-review" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
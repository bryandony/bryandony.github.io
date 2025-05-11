---
layout: archive
title: "Group Members"
permalink: /group/
author_profile: true
---

{% include base_path %}

## PhD Students
{% for post in site.group %}
  {% if post.type == "phd" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## MS Students
{% for post in site.group %}
  {% if post.type == "ms" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## BS Students
{% for post in site.group %}
  {% if post.type == "bs" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Visitors
{% for post in site.group %}
  {% if post.type == "visitor" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Former
{% for post in site.group %}
  {% if post.type == "former" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
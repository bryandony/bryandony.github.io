---
layout: archive
title: "Group Members"
permalink: /grouptest/
author_profile: true
---

{% include base_path %}

## PhD Students
{% for post in site.group %}
  {% if member.type == "phd" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## MS Students
{% for post in site.group %}
  {% if member.type == "ms" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## BS Students
{% for post in site.group %}
  {% if member.type == "bs" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Visitors
{% for post in site.group %}
  {% if member.type == "visitor" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
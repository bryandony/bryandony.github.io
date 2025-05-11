---
layout: archive
title: "Group"
permalink: /grouptest/
author_profile: true
---

{% include base_path %}

## PhD Students
{% for post in site.group %}
  {% include archive-single.html %}
{% endfor %}

## MS Students
{% for post in site.ms %}
  {% include archive-single.html %}
{% endfor %}

## BS Students
{% for post in site.bs %}
  {% include archive-single.html %}
{% endfor %}
---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
## Work in Progress

{% include base_path %}

{% for post in site.work_in_progress reversed %}
  {% include archive-single.html %}
{% endfor %}

## Working Papers

{% include base_path %}

{% for post in site.workingpapersreversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
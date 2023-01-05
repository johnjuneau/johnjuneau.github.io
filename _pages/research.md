---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Working Papers

  1. [External Validity and Implementation at Scale: Evidence from a Migration Loan Program in Bangladesh](https://link-url-here.org)
  2. [Migration and the Labor Market Impacts of COVID-19](https://link-url-here.org)
  3. [Herder-Related Violence, Agricultural Work, and the Informal Sector as a Safety Net](https://link-url-here.org)

## Works in Progress

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

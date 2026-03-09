---
layout: archive
title: "Members"
permalink: /members/
author_profile: true
---

{% include base_path %}

## Group leader

{% for member in site.members %}
  {% if member.role == "Group leader" %}
    {% include archive-member.html %}
  {% endif %}
{% endfor %} 

## Postdocs

{% for member in site.members %}
  {% if member.role == "Postdoc" %}
    {% include archive-member.html %}
  {% endif %}
{% endfor %} 

## PhD Students

{% for member in site.members %}
  {% if member.role == "PhD student" %}
    {% include archive-member.html %}
  {% endif %}
{% endfor %} 

## Former members

{% for member in site.members %}
  {% if member.role == "Former member" %}
    {% include archive-member.html %}
  {% endif %}
{% endfor %} 
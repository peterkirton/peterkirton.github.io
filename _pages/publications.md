---
layout: archive
title: "Publications and Preprints"
permalink: /publications/
author_profile: true
---

You can also find our articles on <u><a href="{{site.author.googlescholar}}"> Peter Kirton's Google Scholar profile</a>.</u>


{% include base_path %}


<img src="{{ 'cloud-peter-kirton.png' | prepend: "/images/" | prepend: base_path }}"> 

## Preprints

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %} 


## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Theses

Peter Kirton:  "Fluctuations and Noise in Nanomechanical and Nanoelectrical Devices" can be found <a href = "{{ 'THESIS_PK_FINAL.pdf' | prepend: "/files/" | prepend: base_path }}"><u>here</u></a>

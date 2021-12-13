---
layout: archive
title: "Members"
permalink: /members/
author_profile: true
---



{% include base_path %}
<h2>Researchers</h2>
{% for post in site.members reversed %}
	{% if post.excerpt == "Researchers" %}
   		{% include archive-member.html %}
	{% endif %}
  
{% endfor %}

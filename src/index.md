---
layout: home
title: Deliberations & Determinations
postsHeading: Posts
archiveButtonText: MORE
socialImage: ''
---
Blog for Fantastic Medieval Wargames
 Campaigns Playable with Paper and Pencil

	  	Tags: {% for tag in collections.tagList %}
		{% set tagUrl %}/tags/{{ tag }}/{% endset %}
		<a href="{{ tagUrl | url }}" class="tag">{{ tag }}</a>
		{% endfor %}
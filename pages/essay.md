---
layout: main
description: Esee scrise și redactate de Dreptul la Oraș
keywords: "Lorem ipsum dolor sit amet."
title: Esee
permalink: /essay
css:
  - /assets/css/essay_tiles.css
---
{% include latest.html %}

<h2>Esee</h2>

<div id="wrapper">
    <div id="columns">
        {% for post in site.posts %}
	        <div class="pin">
	            <div class="pinTitle"><a href="{{ post.url }}">{{ post.title }}</a></div>
	            <div class="pinDate">{{ post.date | date: "%d %B %Y" }}</div>
	            <p>{{ post.description }}</p>
	            <a href="{{ post.url }}"><img src="{{ post.image.url }}"/></a>
	        </div>
	    {% endfor %}
	</div>
</div>
---
layout: main
description: Esee scrise și redactate de Dreptul la Oraș
keywords: "Lorem ipsum dolor sit amet."
title: Esee
permalink: /essays
css:
  - /assets/css/essay_tiles.css
---

<h2>Esee</h2>

<div id="wrapper">
    <div id="columns">
        {% for post in site.posts %}
	        <div class="pin">
	            <p>{{ post.date | date: "%d %B %Y" }}  &mdash; <a href="{{ post.url }}">{{ post.title }}</a></p>
               <img src="{{ post.image }}"/>
               <p>{{ post.description }}</p>
	        </div>
	    {% endfor %}
	</div>
</div>
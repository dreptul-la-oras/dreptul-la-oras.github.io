---
id: essay
layout: main
description: Esee scrise și redactate de Dreptul la Oraș
keywords: "essay,esee"
title: Esee
permalink: /writings.html
css:
  - /assets/css/writings_tiles.css
---
<div class="writings">
    <div class="writings-wrap">
        <div class="writings-columns">
            {% for post in site.posts %}
               {% include writing_tile.html
                    url=post.url
                    title=post.title
                    date=post.date
                    image_url=post.image.url
               %}
        </div>
	</div>
</div>
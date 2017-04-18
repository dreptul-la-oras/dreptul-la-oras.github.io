---
id: writings
layout: main_wide
description: Texte scrise și redactate de Dreptul la Oraș
keywords: "essay,esee,writings,texte"
title: Texte
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
            {% endfor %}
        </div>
	</div>
</div>
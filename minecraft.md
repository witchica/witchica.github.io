---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: project_list
title: Minecraft
header-image: "/assets/games/minecraft/compactstorage/1.jpg"
---
<div class="game-list">
{% for game in site.tags["minecraft"] %}

    {% include components/game_card.html cover-image=game.cover-image title=game.title url=game.url %}

{% endfor %}
</div>

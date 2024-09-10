---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: project_list
title: Professional Work
header-image: "/assets/games/tsw-5/wcml-2.png"
---
<div class="game-list">
{% for game in site.tags["professional"] %}

    {% include components/game_card.html cover-image=game.cover-image title=game.title url=game.url %}

{% endfor %}
</div>

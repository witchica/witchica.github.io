---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: project_list
title: Personal Work
header-image: "/assets/games/catjam/0.jpg"
---
<div class="game-list">
{% for game in site.tags["personal"] %}

    {% include components/game_card.html cover-image=game.cover-image title=game.title url=game.url %}

{% endfor %}
</div>

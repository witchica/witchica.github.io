---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: landing
title: Home
header-image: "/assets/games/tsw/class-700-0.jpg"
introduction-header: Hi there! My name is Jess and I'm a technical designer from South East England 🏳️‍🌈.
introduction: "I'm currently working at Dovetail Games on the Train Simulator World franchise in the Rail Vehicle Setup team. My role involves setting up rail vehicles and all of their systems, mirroring their real world functionality into the game, documenting how this has been done as I go and testing how different components interact with one another. This role is super exciting for me as I love trains and it has given me a chance to grow my Unreal Engine skillset.
<br><br>
On the side I'm working on my own little projects, mainly video editing and music these days! If you want to see any of my other work please check out the links below, and if you want to get in contact feel free to email me!"
---

# Professional Work

<div class="game-list">
{% for game in site.tags["professional"] %}

    {% include components/game_card.html cover-image=game.cover-image title=game.title url=game.url %}

{% endfor %}
</div>

# Personal Work
<div class="game-list">
{% for game in site.tags["personal"] %}

    {% include components/game_card.html cover-image=game.cover-image title=game.title url=game.url %}

{% endfor %}
</div>

{% if site.tags["blog"] %}
# Blog Posts

<div class="game-list">
{% for game in site.tags["blog"] %}
    {% include components/game_card.html cover-image=game.cover-image title=game.title url=game.url %}
{% endfor %}
</div>
{% endif %}

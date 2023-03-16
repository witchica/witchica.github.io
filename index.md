---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: landing
title: home
header-image: "/assets/games/catjam/1.jpg"
introduction-header: Hi there! My name is Jess and I'm a technical designer from the UK
introduction: "I'm currently working at Dovetail Games on the Train Simulator World series. My role involves setting up rail vehicles and all of their systems, mirroring their real world functionality into the game, documenting how this has been done as I go and testing how different components interact with one another. This role is super exciting for me as I love trains and it has given me a chance to grow my Unreal Engine skillset.
<br><br>
On the side I'm working on my own little projects, I have a few interesting ideas but nothing fully fleshed out yet! Keep an eye out for more details soon! I have been trying my best to work on game jams to try and get back into making things for myself, and I have a goal of doing 10 game jams in 2023."
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

# Blog Posts

<ul>
{% for post in site.tags["blog"] %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
{% endfor %}
</ul>
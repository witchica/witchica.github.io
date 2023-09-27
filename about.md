---
layout: about
permalink: /about.html
header-image: "/assets/about/16.jpg"
custom-header-css: "background-position-y: 50%;"
title: About Me
sections: [
    {
        "image": "/assets/about/1.jpg",
        "header": "2013",
        "text": "The image here is my first ever Minecraft mod, it added amethysts to the game! I loved rocks and crystals when I was growing up so this was the obvious choice for me to add. From here it spiralled into making creepers blow up 100x what they normally did, adding new mods, furniture etc. until I decided I wante to make something more meaningful. This is when I had the idea to create a mod that added bigger chests to the game."
    },
    {
        "image": "/assets/about/2.jpg",
        "header": "2014",
        "text": "The first version of Compact Storage was very basic compared to where it is now. I simply added 4 new types of chest with incrementally larger storage types this was basic for me even at the time. I then decided I wanted to add more to this mod, I think I initially added one more larger chest. Then, I decide to add a system to make the chests dynamic. This came in the form of a chest builder addition to the mod"
    },
    {
        "image": "/assets/about/3.png",
        "header": "2015",
        "text": "In 2015, I released a more advanced version of my Minecraft mod, CompactStorage! This builder gave users total freedom over their storage, allowing you to change the size from 1x1 to 24x12 with custom recipes This was the most advanced thing I had made in Minecraft at the time and I was really proud of it. At around this time, I also added backpacks to the mod and this is when it starte getting popular! I updated from version to version but eventually it fell off around the 1.12 era. I have since picked the mod back up and I'm happy to be working on it again"
    },
    {
        "image": "/assets/about/4.jpg",
        "header": "March 2019",
        "text": "At some point around 2019, I was in college and messing around with Unity a lot. I wanted to make a game where you dodged cars but I never managed to ge that working! I tried my hardest and followed a lot of tutorials but I was putting myself in a the deep end! I then decided to work on more basic projects and concepts rather than making things difficult for myself"
    },
    {
        "image": "/assets/about/5.jpg",
        "header": "November 2019",
        "text": "During my university course I had to use Unreal engine to create a story based game, I created a game about escaping a building during a fire. I created the narrative structre elements from scratch with Blueprints and I'm really proud of how that system turned out! I haven't got much experience with Unreal but this gave me a good starting place to learn from."
    },
    {
        "image": "/assets/games/electron/2.jpg",
        "header": "February 2020",
        "text": "I participated in the Edinburgh Napier University Global Game Jam in 2020, this was the first time I had taken on a full project rather than makin smaller tech demos. This was super fun and allowed me to explore what it was like to make a game from start to finish. It gave me a chance to explor adding cutscenes into Unity. Doing this game jam sparked my love of game development again and gave me a push to start working on games again."
    },
    {
        "image": "/assets/about/6.jpg",
        "header": "July 2021",
        "text": "Over the first year of the pandemic I took a year out of university. I spent the year working and spending my free time doing little game projects an other stuff I enjoyed. Though, my free time was limited because in the first lockdown I worked 60 hour weeks at Sainsbury's! I spent the first lockdown in-store but then became a driver during the second lockdown! This took me all over the borders and was first bit of inspiration for one of my indie projects!"
    },
    {
        "image": "/assets/about/7.jpg",
        "header": "February 2022",
        "text": "Working at my university was super fun and allowed me to have more freedom whilst I studied. I worked on a project called Let's Play Wester Hailes wher children were tasked with creating games about their local area! I helped in the classrooms and provided support to the researchers, I also worke on an arcade machine launcher for the games! I also got to work at different events for new starts at the uni which was super fun and interesting! A bi thank you to all of the staff at Edinburgh Napier Uni for the amazing time I had there and all of the support! You guys are the best"
    },
    {
        "image": "/assets/about/8.jpg",
        "header": "March 2022",
        "text": "I took the roads for the second time (foreshadowing!), this time with Tesco! Tesco gave me room to decide what to do, as I was coming up on the end of uni and wasn't sure whether to do a postgraduate degree or find a job in the games industry! Working there was a nice break from the usual for me and let me explore the lovely Scottish Borders once more. This led to some nice inspiration for a game set in the Borders!"
    },
    {
        "image": "/assets/about/9.jpg",
        "header": "May 2022",
        "text": "I spent 4th year at university working on my Gallery of Safe Space project. I initially envisioned the project as a way to explor representation of trans people within new media types such as VR. However, I ended up exploring safe spaces instead! This was super interestin as it allowed me to apply my game dev skills to a serious topic. I really enjoyed the last year of university and I also worked at the uni whilst studying."
    },
    {
        "image": "/assets/about/10.jpg",
        "header": "July 2022",
        "text": "I got my first industry job! Working on Train Sim World has given me a very vast understanding of Unreal Engine and the Blueprint system. It also allowed me to lear how office roles operate and how teams communicate and work together. My main tasks so far have been setting up the rail vehicles for the game, which invovles a lot of 400 page manual and replicating systems in blueprint. It's super fun working on one of the games that I have played and learning how it goes together. Working remotely has been really interesting as well as I've developed a whole new work-life balance within my own home! This role has been super benificial in broadening my understanding of the game industry."
    },
    {
        "image": "/assets/about/14.jpg",
        "header": "March 2023",
        "text": "So, this is where I am right now! I'm currently working away at Dovetail on TSW, working on my ideas in my spare time and seeing what happens next! I'm super excited to be working on my own projects and I find it super exciting seeing what possibilities are out there. I can' wait to see what 2023 brings and what new things await me! Maybe there'll be another section about it on here soon! 🎉"
    },
    {
        "image": "/assets/about/17.jpg",
        "header": "July 2023",
        "text": "Wow! So much happened in such a short amount of time... I now live in the South of England?! I got promoted at Dovetail to Technical Designer Level 1 and discovered that having hobbies is fun! I now work on video production and music projects in my free time instead of spending ALL of my time working on games! Jessica used Hobbies! It's Super Effective! Lame joke, I know. But seriously, burn out has been rough lately and having little things to do has really helped. I'm excited to see where video and music stuff takes me, all whilst working away at my tech design job!"
    }
]
---

{% for section in page.sections %}
 {% include components/about_card.html section=section %}
{% endfor %}
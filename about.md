---
layout: about
permalink: /about.html
header-image: "/assets/about/12.jpg"
custom-header-css: "background-position-y: 70%;"
title: About Me
sections: [
    {
        "image": "/assets/about/1.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/2.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/3.png",
        "text": ""
    },
    {
        "image": "/assets/about/4.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/5.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/6.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/7.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/8.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/9.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/10.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/11.jpg",
        "text": ""
    },
    {
        "image": "/assets/about/12.jpg",
        "text": ""
    }
]
---

{% for section in page.sections %}
 {% include components/about_card.html section=section %}
{% endfor %}
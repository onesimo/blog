---
layout: default
title: About me 
cover: '/assets/images/chile_atacama_06.jpeg'
---

<header class="main-header {% if page.cover %}" style="background-image: url({{ page.cover }}) {%else%}no-cover{% endif %}">
    <nav class="main-nav overlay clearfix">
            {% if page.logo %}
                <a class="blog-logo" href="{{ site.baseurl }}">
                    <img src="{{ page.logo }}" alt="Blog Logo" />
                </a>
            {% endif %}
        <a class="subscribe-button icon-feed" href="{{ site.baseurl }}feed.xml">Subscribe</a>
    </nav>
     
    <a class="scroll-down icon-arrow-left" href="#content" data-offset="-45"><span class="hidden">Scroll Down</span></a>
</header>

Here we are again, here is me, I little poor guy.

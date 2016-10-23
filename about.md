---
layout: page
title: About me 
cover: '/assets/images/chile_atacama_0.jpeg'
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
    <div class="vertical">
        <div class="main-header-content inner">
            <h1 class="page-title">{{ site.name }}</h1>
            <h2 class="page-description">
                {% if site.description %} {{ site.description }}. {% endif %}
                {% if page.about %} <a href='{{ site.baseurl }}{{ page.about }}'> About me </a> {% endif %}
            </h2>
        </div>
    </div>
    <a class="scroll-down icon-arrow-left" href="#content" data-offset="-45"><span class="hidden">Scroll Down</span></a>
</header>

This is a static page. It could be an 'about page' if you'd like.

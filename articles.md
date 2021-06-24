---
title: Articles
layout: page
permalink: /articles/
intro_image_absolute: true
intro_image_hide_on_mobile: false
---

<div class="container pt-6 pb-6">
    {% for post in site.posts %}
    <div class="row">
        <div class="mb-2"> 
            <div class="team team-summary team-summary-large">
                <div class="team-meta">
                    <h2 class="team-name"><a href="{{post.url}}">{{post.title}}</a></h2>
                    <p class="team-description">{{ post.date | date_to_long_string }}</p>
                </div>
                <div class="team-content">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magn...</p>
                </div>
                <a href="{{post.url}}">Read More</a>
            </div>
        </div>
    </div>
  {% endfor %}
</div>


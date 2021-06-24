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
        <div class="col-12 col-md-12 mb-2">
            <div class="team team-summary team-summary-large">
                <div class="team-meta">
                    <h2 class="team-name"><a href="/team/peter-van-eijk/">{{post.title}}</a></h2>
                    <p class="team-description">{{post.date}}</p>
                </div>
                <div class="team-content">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magn...</p>
                </div>
            </div>
        </div>
    </div>
  {% endfor %}
</div>


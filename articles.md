---
title: Articles
layout: teams
permalink: /articles/
intro_image_absolute: true
intro_image_hide_on_mobile: false
---

# Articles

<div class="container pt-6 pb-6">
    {% for post in site.posts %}
    <div class="row">
        <div class="col-12 col-md-12 mb-2">
            <div class="team team-summary team-summary-large">
                <div class="team-image">
                    <img alt="Peter Van Eijk" class="img-fluid mb-2" src="/images/team/peter-van-eijk-711986-unsplash.jpg">
                </div>
                <div class="team-meta">
                    <h2 class="team-name"><a href="/team/peter-van-eijk/">Peter Van Eijk</a></h2>
                    <p class="team-description">Director</p>
                    <a target="_blank" href="https://www.linkedin.com/">LinkedIn</a>
                </div>
                <div class="team-content">
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magn...</p>
                </div>
            </div>
        </div>
    </div>
  {% endfor %}
</div>


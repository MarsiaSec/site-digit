---
layout: news
title: Release party au Rockn'eat
description: Release party pour la sortie de l'album Sourate Safran au Rockn'eat.
image: assets/images/banniere_rockneat.jpg
---



<!-- Main -->
<div id="main" class="alt">
    <div class="video-list">
        <div class="video-item">
            <iframe width="100%" height="100%" src="https://www.youtube.com/embed/kp2aXl4FePs?si=3dXuNPHeCrIet1Xb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </div>

<!-- Content -->
<div class="box alt">
    <div class="row 50% uniform">
        {% assign photos = site.static_files | where: "image", true %}
            {% for image in photos %}
                {% if image.name contains "rockneat" %}
                <div class="4u">
                        <span class="image fit">
                            <img src=" {{ site.baseurl }}{{ image.path }}" alt="" />
                        </span>
                </div>
                {% endif %}
            {% endfor %}

    </div>
</div>

</div>

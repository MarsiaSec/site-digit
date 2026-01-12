---
layout: news
title: Concert à la Vache Rouge
description: Concert au restaurant La Vache Rouge.
image: assets/images/banniere_vache_rouge.jpg
---


<!-- Main -->
<div id="main" class="alt">

<div class="video-list">
    <div class="video-item">
        <iframe width="100%" height="100%" src="https://www.youtube.com/embed/nBIG9TNJ5AA?si=Uz7OfVvb70UtMPNb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
</div>

<!-- Content -->
<div class="box alt">
    <div class="image-board">
        {% assign photos = site.static_files | where: "image", true %}
            {% for image in photos %}
                {% if image.name contains "vache_rouge" %}
                        <span class="image-board-item">
                            <img src=" {{ site.baseurl }}{{ image.path }}" alt="" />
                        </span>
                {% endif %}
            {% endfor %}

    </div>
</div>

</div>

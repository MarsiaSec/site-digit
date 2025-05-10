---
layout: news
title: Concert à la Vache Rouge
description: Concert au restaurant La Vache Rouge
image: assets/images/banniere_vache_rouge.png
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/nBIG9TNJ5AA?si=Uz7OfVvb70UtMPNb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


<!-- Main -->
<div id="main" class="alt">

<!-- Content -->
<div class="box alt">
    <div class="row 50% uniform">
        {% assign photos = site.static_files %}
            {% for image in photos %}
                {% if image.name contains "vache_rouge" %}
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

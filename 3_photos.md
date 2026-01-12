---
title: PHOTOS
layout: photos
description: 
image: assets/images/024_digitipus.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
    <div class="inner">
        <header class="major">
            <h1>Photos</h1>
        </header>
<!-- Content -->
        <span class="image fit">
            <img src="{% link assets/images/banner.jpg %}" alt="" />
        </span>
<div class="box alt">
    <div class="image-board">
        {% assign photos = site.static_files | where: "image", true %}
            {% for image in photos %}
                        <span class="image-board-item">
                            <img src=" {{ site.baseurl }}{{ image.path }}" alt="" />
                        </span>
            {% endfor %}
    </div>
</div>

    </div>
</section>

</div>

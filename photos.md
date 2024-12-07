---
title: PHOTOS
layout: photos
description: 
image: assets/images/IMG_3762.jpg
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
    <div class="row 50% uniform">
        {% assign photos = site.static_files | where: "image", true %}
            {% for image in photos %}
                <div class="4u">
                        <span class="image fit">
                            <img src="{{image.path }}" alt="" />
                        </span>
                </div>
            {% endfor %}
    </div>
</div>

    </div>
</section>

</div>

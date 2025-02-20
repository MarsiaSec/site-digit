---
title: ACTUALITÉS
layout: news
description: 'Toutes les prochaines dates de concert, sorties et nouveautés du groupe.'
image: assets/images/news.jpg
nav-menu: true
---

<section id="two" class="spotlights">
	{% for post in site.posts %}
	<section>
		<a href="{{ site.baseurl }}{{ post.url }}" class="image fit">
			<img src="{{ post.image }}" alt="" data-position="center center"/>
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>{{ post.title}}</h3>
				</header>
					<p>{{ post.description }}</p>
				<ul class="actions">
					<li><a href="{{ site.baseurl }}{{ post.url }}" class="button">En savoir plus</a></li>
				</ul>
			</div>
		</div>
	</section>
	{% endfor %}
			<!--
	<img src="{% link assets/images/035_digitipus.jpg %}" alt="" data-position="top center" />
			<img src="{% link assets/images/035_digitipus.jpg%}" alt="" data-position="25% 25%" />
	 -->
</section>


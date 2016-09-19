---
layout: page
title: Photos
permalink: /photos/
gallery-enabled: true
---
<!--Any additional images must be added in the gallery-photos dir. Metadata must go in the gallery-photo-metadata.csv -->

<div id="links">
	<table>
	{% for metadata in site.data.gallery-photo-metadata %}
		{% assign mod = forloop.index | modulo: 3 %}
		<div class="col-md-4">
			<a href="{{ site.url }}/assets/gallery-photos/{{ metadata.path }}" 
			title="{{ metadata.title }}, {{ metadata.date }}" data-gallery>
				<img src="{{ site.url }}/assets/gallery-photos/{{ metadata.path }}" alt="{{ metadata.title }}, {{ metadata.date }}" class="gallery-image">
			</a>
		</div>
	{% endfor %}
	</table>
</div>
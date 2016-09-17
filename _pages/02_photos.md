---
layout: page
title: Photos
permalink: /photos/
gallery-enabled: true
---
<div id="links">
	{% for metadata in site.data.gallery-photo-metadata %}
		<a href="{{ site.url }}/assets/gallery-photos/{{ metadata.path }}" title="{{ metadata.title }}, {{ metadata.date }}" data-gallery>
			<img src="{{ site.url }}/assets/gallery-photos/{{ metadata.path }}" alt="{{ metadata.title }}, {{ metadata.date }}">
		</a>
	{% endfor %}
</div>
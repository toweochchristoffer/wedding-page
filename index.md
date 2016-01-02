---
layout: article
permalink: /
title: "Front page"
---
<h1>Front page</h1>
<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
{{site.url}}
</div><!-- /.tiles -->

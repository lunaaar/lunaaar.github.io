---
layout: default
title: Game Dev
---
<div class="projects">
{% for game in site.data.gamedev_projects %}
	<div class="project" style="clear: left">
		<p style="float: left">
			<img src ="{{game.image}}" alt="{{game_paths.title | escape}}" height="200" width="300">
			<p><h2><u>{{game.name}}</u></h2>
			{{game.description}}<br>
			<a class="page-link" href="{{ game.link | relative_url }}">{{ game.name | escape }}</a><br>
			</p>
		</p>
	 </div>
{% endfor%}
</div>

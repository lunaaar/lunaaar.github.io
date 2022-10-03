---
layout: home
title: Home
description: Personal Website
---

<style>

	@font-face{
		font-family: Phonk; src: url('/assets/Phonk Regular Demo.otf')
	}
	h1{
		font-family:Phonk;
	}

	aside{
		float:left;
		width: 25%;
		margin: 0 1%;
		background-color: #C8A2C8;
		padding: 5px;
	}
	section{
		float: right;
		width: 69%;
		margin: auto;
		background-color: yellow;
	}
</style>
<body>
	<aside>
		<center>
			<img src="{{site.pfp | relative_url}}" width="75%" height="75%">
			<h2 style="font-family:polli sans">About Me</h2>
		</center>
		<p>Hi my name is Lunar, I am an aspiring developer looking to push into the game dev industry.
		</p>
		<center>
			<a href="https://github.com/{{ site.github_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use></svg></a>
			<a href="https://www.linkedin.com/in/{{ site.linkedin_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg></a>
			<a href="https://www.twitter.com/{{ site.twitter_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#twitter' | relative_url }}"></use></svg></a>
		</center>
	</aside>
	<section>
		<div style="background-color: red">
			<center>
				<h1> Projects</h1>
			</center>
			<aside style="float:right">
				<img src="{{site.game_dev | relative_url}}">
			</aside>
			<section style="float:right; background-color: green">
				test2
			</section>
		</div>
	</section>
</body>
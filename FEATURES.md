Muffin Features
-------------------

.Colour Variables (via Color Me SASS)

	body{
	background-color: $orangeDark;
	color: $whiteFloral;
	}


.SVG Icons  (via Font Awesome)

	Say Cheese <i class="icon-camera-retro"></i>
	Say Cheese <i style="font-size:5em" class="icon-camera-retro"></i>


.SASS media queries

	pre{
	font-size: 1.5em;

	@include respond-to(medbig) { 
		font-size: 1em;
	}
	}


.HTML Includes (via Jekyll)

	<div class="about-page">
	{% include bluth_ipsum.html %}
	</div>


####Working on writing up a few more so hold tight.
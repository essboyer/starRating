# Star Rating

A quick 'n dirty jQuery plugin to generate a 0-5 star rating. 
It uses &amp; requires [FontAwesome!](http://fortawesome.github.io/Font-Awesome/) webfont to generate the stars.

# Usage

```HTML

<div id="stars"></div>
...

$("#stars").starRating(3.5);

```

# Result
The resulting markup produced is minimal and completely controllable with CSS.

```HTML

<div class="starRatingBox">
	<i class="fa fa-star"></i>
	<i class="fa fa-star"></i>
	<i class="fa fa-star"></i>
	<i class="fa fa-star-half"></i>
	<i class="fa fa-star-o"></i>
</div>

```

# Requirements

* [jQuery](http://jquery.com)
* [FontAwesome!](http://fortawesome.github.io/Font-Awesome/)
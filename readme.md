<p align="center">
    <a href="http://hung.su/">
		<img src="https://raw.githubusercontent.com/hungsu/hung.su-2018/master/images/logo--black.png" alt="Hung-Su logo" title="Hung-Su" height="120" />
	</a>
</p>
<p align="center">
	<a href="https://app.codeship.com/projects/297107">
		<img src="https://app.codeship.com/projects/061b9b00-6499-0136-9075-32f9241b3bc4/status?branch=master">
	</a>
	<a href="https://twitter.com/HungSu">
		<img src="https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow">
	</a>
	<a href="https://app.codeship.com/projects/297107">
		<img alt="Uptime Robot ratio (30 days)" src="https://img.shields.io/uptimerobot/ratio/m780675982-18212a6f5dfd729a0884579a.svg">
	</a>
</p>
A curated page of my best work and working methodology

* [Methodology](#methodology)
* [Deployment and hosting](#deployment-and-hosting)
* [Goals and metrics](#Goals-and-metrics)

## Methodology

This project uses a Lean, document driven methodology. That is, no assets will be created aside from what will ultimately be used in the final product. This means:

* No separate project tracker
* No separate wiki or documentation. All documentation will be in this readme, or in code comments
* All prototyping/sketched assets will be saved here as part of documentation
* All graphic source files (Icons, photos) will be saved here

## Deployment and hosting
This project will use Continuous Delivery. That is, any commits will automatically be deployed to [hung.su](http://hung.su) using [Codeship](https://app.codeship.com/hungsu). The project will be hosted on a private VPS running NGINX so that we have HTTPS, HTTP2

## Goals and metrics
In approximate order of importance
* Compel people with UI job opportunities to email me about them
* Be visually pleasing by 2018 standards
	* Instagram [#webdesign](https://www.instagram.com/explore/tags/webdesign/) [#ui](https://www.instagram.com/explore/tags/ui/)
	* Facebook
	* Reddit
* Be fast and lightweight
	* Speedindex. This repository should automatically run tests against WebPageTest and maintain a speedindex under 1000
	* https://github.com/ai/size-limit
* Be accessible

## Technology

* No frameworks at all, such as Vue. This will be a simple HTML/CSS/JS website for performance.
* No javascript analytics, for speed
* Must be responsive, probably with CSS media queries
* Use a CDN like Cloudinary to send tiny images
* If I must use first screen image, try this https://css-tricks.com/the-blur-up-technique-for-loading-background-images/
* Must have unobtrusive animation
	* https://popmotion.io/
* Must look good on these browsers:
	* Win Chrome
	* Win Firefox
	* Mac Chrome
	* Mac Firefox
	* Android Chrome
	* iPhone Safari
	* iPhone Chrome
* Automatic formatting with https://github.com/nrwl/precise-commits

# Style
* Light and dark theme?
* Use IDE color scheme? https://news.ycombinator.com/item?id=17485706
	* http://ethanschoonover.com/solarized#features
	* https://github.com/morhetz/gruvbox
	* https://github.com/jacoborus/tender.vim

# Inspiration
* http://renvoye.com/
	+ Cute animations - notably the rooster, and pen
	+ Work takes up large amounts of screen real estate as it should
	+ "My Impact" is great copywriting
	- Animations feel slow
	- Scrolling feels slow
* https://brutalist-web.design/
* Timeless design https://www.imaginarycloud.com/blog/timeless-classic-ui-design/amp/


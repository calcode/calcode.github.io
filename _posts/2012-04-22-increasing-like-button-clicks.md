---
layout: post
title: Increase Like Button Clicks on Informational Sites
date: 2012-04-22 15:18
author: calum
comments: true
categories: [Digital Marketing, SEO, Social, Technology]
---
<strong>A colleague of mine <a title="Ross Tavendale" href="http://rosstavendale.com/">Ross Tavendale</a> highlighted </strong>the idea of placing social sharing functionality alongside content on informational sites. A great idea for highlighting specific gems likely to be shared, as button placement currently tends to be commonly top / bottom. Some further discussion and a bit of further research this as being a nice little way of potentially increasing the rate at which people interact with social sharing functionality. Essentially what he described is a route to increasing Like Button clicks on informational sites, in turn expanding your visibility and following on Facebook.

<!--more-->

<blockquote><strong>I wanted to find out exactly how this could work, alongside any potential benefits and impact points - this took a little more digging</strong></blockquote>
It is quite common for e-commerce websites to achieve additional Like button clicks through making use of Facebook Open Graph mark-up, declaring products as objects and placing buttons alongside to aid in sharing. This works really well for people thinking about making a purchase, or people about to make a purchase and sharing it to friends and families in advance. <a href="http://www.asos.com">ASOS</a> is a great example of this.

<a href="http://calumshep.com/wp-content/uploads/2012/04/asos-like-button-example.png"><img class="alignright size-thumbnail wp-image-128" title="asos-like-button-example" alt="" src="http://calumshep.com/wp-content/uploads/2012/04/asos-like-button-example-150x150.png" width="150" height="150" /></a>

This e-commerce method works because your single page is a single object, a product. However, how does this work when you are looking to share a specific area of a page on an informational site, without impacting messaging when sharing the page as a whole? This is the aspect that interested me, as I wanted to know how they were pulling it off and if there were any search implications.

Well, let’s take a look at the example Ross initially provided in the form of <a href="http://www.britain-magazine.com/">Britain Magazine</a>.

<a href="http://calumshep.com/wp-content/uploads/2012/04/brittish-quote-button1.png"><img class="alignright size-thumbnail wp-image-127" title="brittish-quote-button" alt="" src="http://calumshep.com/wp-content/uploads/2012/04/brittish-quote-button1-150x150.png" width="150" height="150" /></a>

Britain Magazine increases Facebook Like Button clicks through adding the ability to share quotes on a page out to Facebook. However, the challenge is that you can only make use of one set of Open Graph mark-up per page, meaning that your entire page would have to become about one single quote, even though it will be providing information above and beyond that.
<h2>How do they do it?</h2>
Simple! They use one Like button for the homepage, then on the same page link through to unique URL’s for each quote, with unique, relevant Open Graph mark-up.

<a href="http://calumshep.com/wp-content/uploads/2012/04/like-button-code-image.png"><img class="alignright size-full wp-image-122" title="like-button-code-image" alt="" src="http://calumshep.com/wp-content/uploads/2012/04/like-button-code-image.png" width="1137" height="91" /></a>

This means that every quote has its own unique URL, so <strong>you aren’t actually sharing THAT quote, your sharing the same quote but on a different URL</strong> (Something the typical user will never realise). You can see the true URL you are sharing within the iFrame.
<h2>Let’s map this out</h2>
<ul>
	<li>Visitor lands on <a href="http://www.britain-magazine.com/">http://www.britain-magazine.com/</a></li>
	<li>Visitor clicks the like button next to the quote</li>
	<li>Visitor shares <a title="http://www.britain-magazine.com/special-post/quotes/alfred-tennyson/" href="http://www.britain-magazine.com/special-post/quotes/alfred-tennyson/">http://www.britain-magazine.com/special-post/quotes/alfred-tennyson/</a>, a unique URL which only provides a single quote and no other content</li>
</ul>
<h2>GREAT idea, however has multiple impact points</h2>
<ul>
	<li>Google will crawl these URLs, thus for every quote a unique URL may be indexed</li>
	<li>When shared, visitors will arrive on a page with a quote and navigation, not the original section of the homepage where the quote was shared from</li>
	<li>A likely increase in like button clicks for your site's content as a whole</li>
</ul>
Essentially, it provides a good route to increased like button clicks, visibility and brand interaction. Alongside, it potentially provides minimal search value and some indexing issues unless spider controls are used e.g. noindex. <strong>All in all, a great idea! </strong>

---
layout: post
title: Increase Like button clicks on informational websites
permalink: increasing-like-button-clicks/
---
A colleague of mine [Ross](http://rosstavendale.com/) highlighted the idea of placing social sharing functionality alongside content on informational sites. A great idea for highlighting specific gems likely to be shared, as button placement currently tends to be commonly top / bottom. Some further discussion and a bit of further research this as being a nice little way of potentially increasing the rate at which people interact with social sharing functionality. Essentially what he described is a route to increasing Like Button clicks on informational sites, in turn expanding your visibility and following on Facebook.

> I wanted to find out exactly how this could work, alongside any potential benefits and impact points - this took a little more digging

It is quite common for e-commerce websites to achieve additional Like button clicks through making use of Facebook Open Graph mark-up, declaring products as objects and placing buttons alongside to aid in sharing. This works really well for people thinking about making a purchase, or people about to make a purchase and sharing it to friends and families in advance. [ASOS](http://www.asos.com) is a great example of this.

<img src="http://uploads.calumshep.com/asos-like-button-example.png"/>

This e-commerce method works because your single page is a single object, a product. However, how does this work when you are looking to share a specific area of a page on an informational site, without impacting messaging when sharing the page as a whole? This is the aspect that interested me, as I wanted to know how they were pulling it off and if there were any search implications.

Well, let’s take a look at the example Ross initially provided in the form of [Britain Magazine](http://www.britain-magazine.com/).

<img src="http://uploads.calumshep.com/british-quote-button.png"/>

Britain Magazine increases Facebook Like button clicks through adding the ability to share quotes on a page out to Facebook. However, the challenge is that you can only make use of one set of Open Graph mark-up per page, meaning that your entire page would have to become about one single quote, even though it will be providing information above and beyond that.

##How do they achieve this?
Simple! They use one Like button for the homepage, then on the same page link through to unique URL’s for each quote, with unique, relevant Open Graph mark-up.

<img src="http://uploads.calumshep.com/like-button-code-image.png"/>

This means that every quote has its own unique URL, so you aren’t actually sharing THAT quote, your sharing the same quote but on a different URL (Something the typical user will never realise). You can see the true URL you are sharing within the iFrame.

##The user journey
- Visitor lands on [http://www.britain-magazine.com](http://www.britain-magazine.com/)
- Visitor clicks the like button next to the quote
- Visitor shares [http://www.britain-magazine.com/special-post/quotes/alfred-tennyson/](http://www.britain-magazine.com/special-post/quotes/alfred-tennyson/), a unique URL which only provides a single quote and no other content

*A great idea with wider implications*
- Google will crawl these URLs, thus for every quote a unique URL may be indexed
- When shared, visitors will arrive on a page with a quote and navigation, not the original section of the homepage where the quote was shared from
- A likely increase in like button clicks for your site's content as a whole

Essentially, it provides a good route to increased like button clicks, visibility and brand interaction. Alongside, it potentially provides minimal search value and some indexing issues unless spider controls are used e.g. noindex. All in all, a great idea!

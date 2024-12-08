---
layout: post
title: Increase Like button clicks on informational websites
permalink: increasing-like-button-clicks/
---
A colleague of mine [Ross](http://rosstavendale.com/) suggested an interesting idea for increasing social sharing on informational websites. By placing social sharing buttons alongside key content, rather than at the top or bottom of a page, it highlights specific sections of a page that are likely to be shared. This approach could potentially boost the rate at which users interact with social sharing buttons, especially the Facebook Like button, ultimately expanding visibility and followers on Facebook.

> I wanted to explore how this could work and understand its potential benefits—this took a bit more digging

While it’s common for e-commerce websites to boost Like button clicks using Facebook Open Graph mark-up (e.g., declaring products as objects and placing share buttons alongside), this method is tailored to single-product pages. A great example of this is [ASOS](http://www.asos.com) where products are shared easily through social media.

However, the question arose: How does this work on informational sites, where you're not sharing a product but rather specific sections of a page without compromising the message of the page as a whole? This was the aspect that intrigued me, and I wanted to understand how sites were pulling this off—and if there were any potential SEO implications.

Let’s explore an example Ross shared with me: [Britain Magazine](http://www.britain-magazine.com/).

Britain Magazine boosts Facebook Like button clicks by adding the ability to share individual quotes on a page. The challenge, however, is that only one set of Open Graph mark-up can be applied to a page. This means that the entire page would need to be focused on a single quote, despite containing other valuable content.


##How do they achieve this?
It’s quite simple! They use one Like button for the homepage and then link to unique URLs for each quote. These URLs feature their own relevant Open Graph mark-up.

This method ensures that every quote has its own unique URL. The visitor is not technically sharing the quote itself, but the unique URL for that quote—something the typical user won't notice. The actual URL being shared can be seen within the iFrame.

##The user journey
- A visitor lands on [http://www.britain-magazine.com](http://www.britain-magazine.com/)
- The visitor clicks the like button next to a quote
- The visitor shares a unique URL [http://www.britain-magazine.com/special-post/quotes/alfred-tennyson/](http://www.britain-magazine.com/special-post/quotes/alfred-tennyson/), which only provides a single quote and no other content

## A great idea with wider implications*
- SEO Benefits: Google will crawl these unique URLs, meaning each quote could be indexed as a separate page.
- Improved User Experience: When shared, users land on a page with just the quote and navigation, rather than the original section of the homepage.
- Increased Engagement: This method likely increases Like button clicks across the site, helping boost overall engagement with your content.

Essentially, this strategy provides an effective way to increase Like button clicks, improve visibility, and enhance brand interaction. While it may offer minimal SEO value and potential indexing issues (unless spider controls like noindex are used), it’s still a clever and creative way to encourage social sharing and engagement.

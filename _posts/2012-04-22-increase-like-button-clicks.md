---
layout: post
title: Increase Like Button Clicks
permalink: increase-like-button-clicks/
---

A colleague, [Ross](http://rosstavendale.com/), suggested an interesting idea for boosting social sharing on informational websites: place social sharing buttons alongside key content rather than at the top or bottom of the page, drawing attention to the specific sections most likely to be shared. Done well, this could meaningfully increase engagement with sharing buttons - especially the Facebook Like button - and expand visibility and followers on Facebook.

> I wanted to explore how this could work and understand its potential benefits - this took a bit more digging than expected.

E-commerce sites commonly boost Like clicks using Facebook Open Graph markup - declaring products as objects and placing share buttons next to them. That approach is tailored to single-product pages; [ASOS](http://www.asos.com) is a good example of it working well.

The harder question: how does this translate to informational sites, where you're not sharing a single product but specific sections of a page - without undermining the page's overall message? That's what pulled me in, along with the potential SEO implications.

Take an example Ross shared with me: [Britain Magazine](http://www.britain-magazine.com/).

Britain Magazine boosts Like clicks by letting visitors share individual quotes from a page. The catch: only one set of Open Graph markup can apply per page, meaning the whole page would normally need to focus on a single quote - awkward when the page holds plenty of other valuable content.

## How do they pull it off?

Simply enough: one Like button lives on the homepage, and each quote links out to its own unique URL, carrying its own Open Graph markup.

Every quote effectively gets its own page. The visitor isn't technically sharing the quote itself but the unique URL for it - invisible to the average user, though you can see it if you inspect the iFrame.

## The user journey

- A visitor lands on [britain-magazine.com](http://www.britain-magazine.com/)
- They click the Like button next to a quote
- They end up sharing a unique URL - e.g. `britain-magazine.com/special-post/quotes/alfred-tennyson/` - showing just that quote and navigation, nothing else

## A clever idea with wider implications

- **SEO benefit:** Google crawls these unique URLs, so each quote can potentially be indexed as its own page.
- **Better user experience:** Visitors arriving via a shared link land on a clean page with just the quote and navigation, rather than a fragment of the homepage.
- **Higher engagement:** The approach likely increases Like clicks site-wide, boosting overall engagement.

Overall, a clever, low-effort way to encourage social sharing and engagement - though it's worth using spider controls like `noindex` where appropriate, since duplicate-content and indexing issues are the main trade-off.

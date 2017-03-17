---
layout: post
title:  "Analytics"
tags: Journal English
---
Despite working for perhaps the largest Internet company in the world, I must admit I have no idea how to properly write or manage a website. But I guess everybody has to start somewhere, right?

To improve the design and increase user engagement using a data-driven approach, I've integrated a subset of tracking features provided by Google Analytics. Here's how it works, and what I've learned so far.

<!--endexcerpt-->
*****

### What it is
Setting up [Google Analytics][analytics] is pretty straightforward. You sign in using your Google account, register your website, and the tool will generate a Javascript snippet for you to embed in your pages. Once deployed, your dashboard will start showing you a set of basic information about your users. This includes real-time visitor count, browser, device, and country.

It is worth noting that Parallax does **not** have access to other more personal information such as age, gender, or interests. To enable tracking for these categories, many countries have laws that require special [user consent][consent]. Since I do not display any ads on my site, it felt rather pointless to ask for permission to access these information.

### The Data
To give you an idea of what this looks like, here are a few types of graphs I get to see:

1. Visitors by country
![Country](/res/blog/2017-03-16-analytics/country.png)
2. Browsing devices (left) and user acquisition method (right)
![Graphs](/res/blog/2017-03-16-analytics/graphs.png)
3. Behavior flow
![Behavior](/res/blog/2017-03-16-analytics/behavior.png)

All of these graphs and tables provide filtering functionality, so it is possible to look at, for example, percentages of mobile users by country.

### Observations

* The vast majority of my traffic comes from social referrals (i.e. Facebook users) either in Taiwan or the US.
* The average user browses on their phones. Glad I spent all those hours working on a (hopefully) enjoyable mobile reading experience!
* Looking at behavior flow, the click rate of my actual blog post is much lower on mobile than on desktop.

I'd like to discuss my conjecture for #3. Clickable elements on my site have an elevated visual effect when hovered, but that dimension of input is not available to mobile users. To address this without an obnoxious "click to read more" button, I added a little arrow to provide some UI [affordance][affordance] that there is more to read:
![Arrow](/res/blog/2017-03-16-analytics/arrow.png)

Let's wait a few weeks to see whether this actually makes a difference.

### Open questions

One glaring problem I'm trying to solve is user retention. That is, how to get visitors to regularly come back and visit Parallax. Page views have fallen off sharply after my initial announcement on Facebook, and I would like to avoid repeatedly spamming people with updates about new posts.

Potential easy solutions include setting up an RSS feed (do people still use these things?) or a mailing list. I am also learning about sitemaps and other methods of getting my blog posts indexed, so perhaps one day you'll be able to see Parallax appear on your news feed once you've visited a few times. I will most likely write a follow-up article in the future once I figure things out, but in the meantime please do share any tips and tricks you may have :)


[analytics]: https://www.google.com/analytics/analytics
[consent]: https://www.google.com/about/company/user-consent-policy.html
[affordance]: https://en.wikipedia.org/wiki/Affordance

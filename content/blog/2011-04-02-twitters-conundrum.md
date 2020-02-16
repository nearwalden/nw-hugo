---
author: nearwalden@gmail.com
date: 2011-04-02 17:52:26+00:00
draft: false
title: Twitter's Conundrum
type: post
url: /2011/04/02/twitters-conundrum/
categories:
- posts
---

We all know that Twitter is amazing, that everyone is using it, and that it's on the road to making everyone who's involved with it rich.  But if that's the case, why are they [messing around with their developer agreements](http://gigaom.com/2011/02/18/war-is-hell-welcome-to-the-twitter-wars-of-2011/) at the risk of annoying their most loyal partners?





Maybe the answer is that Twitter isn't the financial slam dunk that we all thought.  The problem, I believe, goes back to a fundamental decision that they made early on, and that probably also contributed to their rapid rise. While they concentrated on their own web interface, Twitter created an elegant API which allowed others to develop first-class UIs for the service on every type of system imaginable. A [nice piece](http://gigaom.com/2011/03/12/why-twitter-should-think-twice-about-bulldozing-the-ecosystem/) by Matthew Ingram at GigaOm highlights the benefit of this approach to Twitter:





<blockquote>
Without the help of third-party apps like Tweetie and Tweetdeck, the company likely would not have been nearly as successful at building the network (and a ready-made client like Tweetie certainly wouldn’t have been sitting there waiting to be acquired). But the ecosystem didn’t just build demand for the network — it also helped build and distribute the behavior that now makes Twitter so valuable: the @ mentions, the direct messages, re-Tweets and so on, none of which were Twitter’s idea originally. That created a huge amount of goodwill, and led to the (apparently mistaken) idea of an ecosystem.
</blockquote>





The result of this approach is that Twitter didn't control the user interface for its own service.  Of course they controlled the website, and they offered their own client, but they don't control how Twitter content looks on other desktop clients, or on my blog, or on my non-Twitter phone app.  Twitter says that over 90% of their content is viewed on their own UIs, but independent developers claim its in the 42% range (here's [a good summary on GigaOm](http://gigaom.com/2011/03/15/heres-why-developers-are-scaring-twitter/[])).





Why am I dwelling on this?  Because if you offer and service that doesn't embed a commerce transaction, and you don't control your UI, the only way you can make money is to have people pay directly for your service.  You may argue with my assertion (Tim Bray and I have been going back and forth on it), but I haven't found a counterexample.





Here's my case.  First, I included the phrase "doesn't embed a commerce transaction"  for reason.  Tim's first comeback was that Googles AdSense and AdWords APIs make money without a UI, but I categorize those as commerce APIs - they are explicitly about the exchange of money for a measurable service (showing ads).





Beyond that, there are presumably a number of ways Twitter could try to monetize their service, so lets look at each of them:






  1. They could charge a fee for using the Twitter service.  I'm sure that they believe this would be suicide - that they'd quickly be replaced by some similar service that had some way to monetize itself without a subscription (or maybe just a purely free alternative - more about that in the follow-on post).
  2. They could embed ads in the results they return.  Their own clients would presumably show the ads, but other UIs would naturally try to strip them out.  
  3. They could protect the ads in their results through their terms of service (Tim suggested this).  Maybe, but then they get into specifying how big the ads have to be, possibly splitting revenue with the other developers, etc.  Once you do that you might as well....
  4. Get rid of all of the other clients so that you can control the UI and monetize it to your heart's content.  




So if you're starting a social networking company of some kind, control your own UI.  Expose select APIs which enhance the desirability of your service, but not ones which restrict your ability to monetize the users' experience.





Finally, this whole discussion of Twitter and how it might monetize itself raises an interesting question:  could someone build an open, federated alternative?  I'll explore that idea in the next post.




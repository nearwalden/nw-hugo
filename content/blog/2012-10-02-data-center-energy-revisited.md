---
author: nearwalden@gmail.com
date: 2012-10-02 05:28:21+00:00
draft: false
title: Data Center Energy, Revisited
type: post
url: /2012/10/02/data-center-energy-revisited/
categories:
- posts
tags:
- computing
---

Knowing my longstanding interest in computing and sustainability, a number of people sent me the NYT article, [_Power, Pollution and the Internet_](http://www.nytimes.com/2012/09/23/technology/data-centers-waste-vast-amounts-of-energy-belying-industry-image.html?pagewanted=6&ref=technology&pagewanted=all&_r=0) on the inefficiencies of data centers (or as the link to the article says, "data-centers-waste-vast-amounts-of-energy-belying-industry-image.html").





Here are my thoughts on some of the points raised by the article, and a closing thought on the messenger itself.





**Do data centers use lots of energy?** Absolutely.  The number in the article says that data centers sustain around 30 billion watts, which I won't argue with.  But while that is a lot of energy, it's only around 0.2% of the sustained, worldwide energy use (~ 17 trillion watts) or 1.3% of the worldwide electricity use. On the other hand, datacenter energy use is growing rapidly (at one point it was doubling every 5 years or so), so even though its small it does deserve ongoing attention.





**Are data centers becoming more efficient?**  Yes.  I don't have data, but by the traditional measure of units of work divided by units of energy, data centers have gained more efficiency in the last 10 years than any other industry.  Part of it is due to the ongoing improvements in silicon (captured elegantly by Moore's Law), but there have been major improvements in datacenter design, cooling, power distribution, system utilization (through virtualization and other technologies), and other optimizations.  There has been lots of healthy exchange among data center professionals which has raised awareness and spread knowledge of best practices.





**Wait a minute, I thought data center people were all secretive.**  Some are, and for very good reason: data centers can represent a huge amount of value in a very small amount of space, so people are nervous about protecting those locations from a wide variety of physical, electrical and digital threats.   However, I found the overall industry to be very open, with lots of useful information changing hands between companies about best practices, etc.  The [Open Computing Project](http://opencompute.org) and [Green Grid](thegreengrid.org) are examples of publicly visible activities, and there is a lot more going on among professionals of different companies behind the scenes.  This is an area where the NYT author had to work hard to ignore reality in order to support the point he wanted to make.





**Is backup power a problem?**  Definitely, but mainly because there is no reliable alternative to diesel generators for long-term (more than a few minutes) backup electricity.  Hospitals use the same thing (a future NYT expose?) and for the same reasons.  This also leads to the next question….





**Do all of these applications and databases really need this much backup power and instant-on capability?**  First, there is a practical issue that its hard to go through a datacenter and decide what you can turn off.  My family reunion pictures may be on the same disk as the photos that show up on nytimes.com, so that I may be happy if they power the disk down periodically, but the general manager of the Times online business would be really upset. This kind of interconnectedness and complexity make it difficult to really turn things off.  Second, there is a great opportunity for gathering work into as few of systems as possible, and turning off the rest until they are needed.  Virtualization tools are advancing quickly, and some of the better run facilities are doing this to some extent already, so I think you'll see much more if it in coming years.  Third, this is really a question of perceived value and who gets to make the choices.  Every operating data center is being paid for by someone who has decides each month with their wallet that this degree of insurance is worth it.





**But couldn't these people save money with better designs and operating models?**  They can, and they surely will over time.  Moreover, given the growth of data centers it is vital that they continue to become more efficient.  As I said, this industry has made huge strides already, but there's a growing culture of awareness, measurement and improvement.  Its useful to remember that most of this equipment has a useful life of 4-6 years, so its natural to expect some time lag before best practices role out everywhere.  (Note that compared to most other things that people spend serious money on, this is actually a pretty short useful lifetime.  So it is a partial explanation of why IT can get efficient faster than others.)





**The information technology industry says it is making the world more sustainable.  Is that reality or hype?**  I think there are two layers to this question.  First, I have made the argument for years that it is impossible to envision a future society with simultaneously higher standard of living and greater sustainability, that does not have broader use of information technology than we have today. Technology continues to help us improve the processes we have, dematerialize goods and services, and rethink our economy.  However, information technology is a tool, not a service in and of itself.  The technology doesn't make us more sustainable, its only certain applications of the technology that does, and those application are done by the IT industry's customers, not the industry itself (note that I said "certain applications" - most uses of IT are not net sustainability gains).  So even at Sun I was very wary of taking credit for the application of IT, and argued against that viewpoint in works like the [SMART 2020 report](http://www.smart2020.org/publications/).





**Didn't you have one last comment?**  As a Chief Sustainability Officer I developed the habit of taking sustainability critiques and applying them to their authors.  For example, I used to wonder what basis Gartner had for critiquing our sustainability plans, when they didn't have any themselves.





In this case that analysis is almost absurdly funny.  Let's review the main themes of the article with respect to The New York Times Company.  _Sustainability_:  the Times' primary business model today is to cut down trees, grind them up to make newsprint and drive them to stores and homes in the middle of the night using a large fleet of vehicles. It is broadly agreed on the Internet that the Sunday Times results in 60,000 to 75,000 trees being cut down each week.  The company could move to full digital delivery, but doesn't have a business model to support that, so keeps chopping down trees.  _Utilization_:  only a tiny fraction of what the Times delivers to customers is read.  A major fraction of the trees they chop down are used to print ads that their readers don't actually want.  _Transparency_: the Times itself has no sustainability report, no report of electricity usage, and no environmental impact statement.  The only thing on their [social responsibility webpage](http://www.nytco.com/social_responsibility/index.html) is marketing fluff.





I see that this is the first in a series for the Times - I'll be looking forward to reading it and digging up more info on them also.




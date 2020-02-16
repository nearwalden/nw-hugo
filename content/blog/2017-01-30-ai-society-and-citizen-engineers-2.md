---
author: nearwalden@gmail.com
date: 2017-01-30 10:58:15+00:00
draft: false
title: AI, Society and Citizen Engineers
type: post
url: /2017/01/30/ai-society-and-citizen-engineers-2/
categories:
- posts
---

![](/images/2017/01/cortical-neural-network.jpg)






Two recent Techcrunch articles highlight some of the challenges we're in for with the increased use of machine learning (ML) and artificial intelligence (AI), to the extent these are separate.  In [_AI’s open source model is closed, inadequate, and outdated_], Kumar Srivastana argues that we need a new kind of transparency (I'm avoiding his use of "open source" - more on that below) because of the complexity and unpredictability of these systems.  Along similar lines, Jeremy Elman and Abel Castilla argue that we need to rethink liability and quality standards in [_Artificial intelligence and the law_].





These articles cover some interesting ground, but are also enlightening in the misconceptions that they reflect. Some specific points:






  1. "Open source" can technically mean one of two things:  1) an organization's decision to make code or other intellectual property visible to others, and 2) a set of licenses organizations that allow to control how others can use material they choose to make visible.  I agree with Kumar that AI and ML introduce some new elements that organizations can choose to make visible, but it's not clear that the decision process of organizations or the licenses we use are the issue.
  2. Even without AI or ML we have many systems that people depend on every day where we have no idea how they work.  Furthermore,  these systems are complex enough that no one truly understands how they will react in different situations (e.g. cascading failures in our electric grid), and we have no visibility into how these systems are being tested, etc.  AI and ML may further complicate this problem, but to portray the situation as brand new and unlike what came before it is not accurate.
  3. Both articles discuss AI's as somehow disembodied beings.  These are algorithms embodied in products and services, where they are generally replacing large, complex pieces of human-written software.  Maybe I'm missing something, but I don't understand how the replacement of one algorithm with another changes the liability of the companies for their products and services.  If my product uses software and it fails in a damaging way, AFAIK the liability should be the same independent of how that software was created.




For me the bottom line is this:  AI and ML are subtle and potentially powerful  tools.  As with any technology, it is the responsibility of product and service companies, and, importantly, their engineers, to understand these tools and use them in a responsible way.   And since these are rapidly evolving technologies, it is incumbent on engineers who use them invest in the time to stay current and keep their systems up to date with the latest methods for testing and validating the algorithms they produce.





Elman and Castilla provide the excellent example of a traffic light that is run by an AI, and the AI decides that the most efficient mode requires the lights to change faster than normal, resulting in more accidents.  The authors cite this example as an example of why we need the law to adapt.  I disagree - this is a clearcut example of engineering culpability.  Just because you use AI or ML for part of an algorithm doesn’t exclude you from putting in some good old-fashioned logic checks in addition.  Think about it:  if a human were controlling the light, wouldn’t we want some logic to make sure they stay within some safety parameters?





Artificial intelligence and machine learning are important new technologies, and they bring some interesting twists.  But this is the next in a very long history of technologies, going back to fire if not earlier, where it is the responsibility of our engineers to translate them into safe uses.  I know that it’s  scary that we can’t look at a piece of code and see exactly what it’s supposed to do, but its foolhardy to believe that with today’s complex systems anyone fully understands what they do and can vouch for them anyway.  

As far as I can tell our existing legal and transparency frameworks and practices haven’t been shown to be outdated by these new technologies, so let’s see how their use evolves and react when our systems break down.




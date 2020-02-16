---
author: nearwalden@gmail.com
date: 2009-07-27 20:05:46+00:00
draft: false
title: Making the Price of Carbon Real
type: post
url: /2009/07/27/making-the-price-of-carbon-real/
categories:
- posts
---

Like many, I'm divided by the passage of Waxman-Markey (aka ACES) in the US House of Representatives. While its passage is a historic event, the bill has so many issues that I find myself as worried as I am excited by it. [ As Tom Friedman recently wrote](http://www.nytimes.com/2009/07/01/opinion/01friedman.html?_r=2) (sorry, free registration required to see the whole article):





<blockquote>
  
> 
> It is too weak in key areas and way too complicated in others. A simple, straightforward carbon tax would have made much more sense than this Rube Goldberg contraption. It is pathetic that we couldn’t do better. It is appalling that so much had to be given away to polluters. It stinks. It’s a mess. I detest it.
  But he immediately turns the tables, saying "Now let’s get it passed in the Senate and make it law.". His main point is that a getting a price on carbon will result in fundamental changes in decision making, which will put us on the right path: 
> 
> 
  
  
> 
> Henceforth, every investment decision made in America — about how homes are built, products manufactured or electricity generated — will look for the least-cost low-carbon option. And weaving carbon emissions into every business decision will drive innovation and deployment of clean technologies to a whole new level and make energy efficiency much more affordable.
  At Sun, we've been a strong advocate for establishing a price for carbon, because Tom is correct that it is a basic requirement for "weaving carbon emissions into every business decision". For example, we'd like to be able to use the current cost of carbon along with scenarios of future costs to make the business case for switching our datacenter backup systems to something less carbon intensive than diesel generators. _Unfortunately, Waxman-Markey doesn't provide a clear price of carbon for America's energy consumers - business or individual_.
> 
> 
</blockquote>





Here's why.





Most homes and businesses, including large ones like Sun, don't emit GHG in ways that require them to directly participate in the cap and trade system. When we purchase electricity the corresponding emissions will have been covered by our electric utility, and when we buy fuel and burn it in vehicles, generators, furnaces, etc, the emissions will have been covered by a party somewhere in the refining and distribution process (ACES smartly avoids forcing each of us individually to participate in the cap and trade system every time we drive somewhere or turn on a lightbulb). In both cases the emissions costs will have been passed along and will show up as increases in our electricity or fuel bill.





The challenge is to figure out what part of our bill went to paying for GHG emissions, since that's the number we need to do a standard return on investment (ROI) analysis like the one described above. Assuming we know the amount of emissions (which you can usually get today), then the number we need is the price per ton that was paid for those emissions.





The obvious answer is to use the current price of carbon in the market where utilities and oil companies trade emissions allowances. But in Waxman-Markey that "market price" may be very different from what your utility or oil company paid. In fact they will have gotten emissions allowances from many different sources, including free allowances from the government, auctioned allowances from the government, domestic offsets, cheaper foreign offsets, "banked" allowances from previous years. Note that these will all usually be cheaper (or much cheaper) than the current "market price", and are not publicly visible. I've verified with folks at utilities and who've worked directly on the bill that there is no provision to make the actual "cost of carbon" available to the consumer, and no utility I've talked to plans to voluntarily provide it.





Since the actual carbon price is lower than the publicly visible price, it makes ROI calculations especially problematic. Using the market price will overestimate the savings of going to a lower-carbon solution, but using any number lower than the market price is pretty much of a guess. This isn't exactly reassuring when you're the one who has to justify a major clean energy investment to your CEO and CFO.





p>Others have argued that the actual price of carbon will be reflected in the consumer prices of the respective energy options, so that decisions can be based off of that. For example, the ACES-adjusted price of coal-based electricity will go up relative to cleaner options, so people will make different decisions. There's two problems with this approach, especially in a business scenario. First, commercial clean energy commitments are almost always multi-year, and extremely so in the case of deploying solar or wind where a 20-year commitment is not uncommon. But it is obviously difficult to do a multi-year ROI analysis without even knowing what the recent carbon costs are as a baseline to project future carbon costs.





The second problem is that the financial advantages of many clean energy options won't show up until the later years of a multi-year analysis. Initial carbon prices will not be high enough to spur a move to cleaner energy, but future carbon prices might. However, to do the financial analysis we again need a combination of recent prices plus a projection of future ones. So while using today's energy prices may work perfectly well for decisions at home, it is inadequate for the type of financial decisions that businesses need to make.





Fortunately this is easy to fix: the cap and trade participants need to make the data available. Here's three possible mechanisms: 
1.  Print the included price of carbon on everyone's bill (or at the pump, in the case of gas, diesel, propane, etc)
2.  Same as above, but assume that this is mostly useful to businesses, so print this data for them only
3.  Each utility or major emitter will publish a monthly or quarterly report of their average price of carbon for the preceding period I believe that any of these would work for us at Sun. The last leaves more to the reader, but makes the data widely available and seems like low effort for the reporting companies. The first and third options make the information available to all US citizens and organizations that will be paying into this system. Personally this form of basic transparency seems like an important ingredient for people to build trust in this complex systems.





If the final version of ACES can establish a visible price for carbon in the US, its value to companies like Sun will rise. But as it exists right now, it does not provide a price for carbon that Sun, or any other company, can use to justify serious efforts to decarbonize our businesses. Addressing this has got to be a top priority as the bill evolves through the Senate and conference.




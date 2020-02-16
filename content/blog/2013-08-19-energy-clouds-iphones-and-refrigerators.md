---
author: nearwalden@gmail.com
date: 2013-08-19 05:59:19+00:00
draft: false
title: Energy, Clouds, iPhones and Refrigerators
type: post
url: /2013/08/19/energy-clouds-iphones-and-refrigerators/
categories:
- posts
tags:
- computing
---

In the last few weeks an idea has been making the rounds that, when you count all of the required networks and cloud services, your iPhone uses more electricity than your refrigerator. This idea was first presented in a publication called [_"The Cloud Begins with Coal"_](http://www.tech-pundit.com/images/2013/07/Cloud_Begins_With_Coal.pdf) by Mark Mills, and was quickly followed up in with further analysis (and a different version of the calculation) by the Breakthrough Institute, [_"Bracing for the Cloud"_](http://thebreakthrough.org/index.php/programs/economic-growth/bracing-for-the-cloud/).  _[Disclosure:  I am proud to be a Sr. Fellow at the Breakthrough Institute.]_





Since these articles make some very interesting points, I decided to dive into the data. I'll share some observations here. At the end I'll take a closer look at the iPhone-fridge comparison.  Teaser: I wouldn't crank up the iPhone guilt just yet.





## Rise of the Wireless Cloud





When I started focusing on the sustainability of computing around 2005, the main area of concern were large, traditional datacenters. Through the next half dozen years the focus shifted to large clouds, including general compute clouds (e.g. Amazon Web Services) and the cloud datacenters behind popular web services (e.g. Facebook, Google, etc).  Multiple football fields in size, these facilities can use the energy of small or medium towns.





These whitepapers highlight the emergence of cellular data (data delivered over the mobile phone network) as a major new area of energy growth in the computing world.  Although mobile data is still a small fraction of overall ITC energy use (less than 10%, and way less by some calculations), it is growing at a rate of multiple hundred percent per year, driven by a combination of increasing subscribers and increasing data usage.





Calculations of energy use for accessing web services, such as Facebook, over a wired or WiFi network have not been very dramatic, as the energy usage was small and spread across the device, the network and the datacenter (WiFi networks, like the one in your home or office, use a tiny fraction of the energy per bit of mobile data networks).  These whitepapers show how dramatically the total energy changes when you include a mobile data network, whose energy cost starts to dominate the result and make the total energy larger by comparison.





In the US and other 'wired' countries (here I literally mean wired) it sometimes feels like mobile data is just a convenience.  Do I really need to upload my pictures this instant, or could I wait until I'm on WiFi?  But in most of the world the mobile Internet _is_ the Internet.  There aren't ubiquitous wires that can carry high speed data, and its unlikely there will ever be any.  For hundreds of millions of people the mobile Internet is the foundation for new ways of life, creating links to other people, information and commerce in ways that were previously unthinkable.





In this way Mills, et al have made an important connection between expanding global Internet access and the resulting increases in energy that the mobile network will require.





Finally, Mills and BTI have touched on four other interesting points, which I cover next.





### ICT Share of WW Energy Use





In the 2007 timeframe there was general agreement that [ICT used roughly 2% of the world's energy](http://www.gartner.com/newsroom/id/503867). Part of why _"...Begins with Coal"_ got attention is because 10% sounded dramatic, but that was a fraction of WW electricity, not all energy.  With electricity around 40% of WW energy use (see [EIA Monthly Report, Table 2.1](http://www.eia.gov/totalenergy/data/monthly/pdf/mer.pdf), that puts ICT at 4% of WW energy, or double what we thought it was 6 years ago.  I have long believed that ICT energy use was doubling every 5 years, so we're more or less on track.





### Lack of Precision in ICT Energy Calculations





Reading the _"...Begins with Coal"_ you see estimates with very large ranges.  One of the key amounts, KWh per GB of mobile data, is described as having a full 10X range of estimated values, from 2 to 20 (more on this in the refrigerator discussion).





A challenge is that the underlying equipment and usage are both changing rapidly.  For example, the [CEET whitepaper](www.ceet.unimelb.edu.au/pdfs/ceet_white_paper_wireless_cloud.pdf?) shows demand growing roughly 400% in 3 years, while the [AT Kearney report](http://www.atkearney.com/documents/10192/760890/The_Mobile_Economy_2013.pdf) (the least reliable of the bunch, IMHO), shows the energy per GB of wireless data dropping over 40% in 2 years.  Unfortunately, Mills doesn't help the situation, as he mixes data from multiple years without any attempt to normalize it.  I was most impressed with the rigor of the CEET whitepaper from this perspective.





### Is Cloud Computing Energy Efficient?





Awareness of the energy involved in the mobile Internet have asked many to wonder whether cloud computing is still efficient.  I'll admit that this is a legitimate question in the wired world (US, Europe, etc), though I strongly believe that any honest accounting will show it is far more efficient than everyone trying to run their own servers.





However, in the majority of the world without wired communications and reliable electricity, where mobile Internet is the Internet, there really isn't a discussion to have: in these areas there is no computing without cloud computing.





### ________Begins with Coal





Since there seems to be acceptance that _Cloud Begins with Coal_, we need to also accept that _EVs Begin with Coal_. I still don't see how EVs are a game changer without a huge breakthrough in renewable electricity, which would be a huge deal all by itself.





## Examining the Calculations





So what uses more energy:  a fridge, or an iPhone?





With everyone agreeing that the Energy Star fridge uses around 350 KWh/year, Mills and BTI take very different approaches to the iPhone calculation.  Mills includes embodied energy, BTI doesn't. This accounts for over 300KWh/year difference.  But if we just focus in on the wireless data, we see two major differences.  First, Mills uses 2 KWh/GB (presumably from CEET), while BTI uses 19 KWh/GB (presumably from AT Kearney).  Second, Mills assumes usage of 2.8 GB/week, or 145.6 GB/year, while BTI uses 1.58GB/month, or 19.1GB/year.  So we have a 9.5x difference in one key value, and a 7.6x difference in the other.





Let's look at energy per GB first.  I looked through a lot of the references, and found no other value over 5 KWh/GB, with most around 2 KWh/GB.  I also independently calculated the value from other data in Mills and CEET, and had one value of 7 KWh/GB using worst case numbers, and other values as low as 1 KWh/GB.  Since the AT Kearney report has no references and doesn't show where the data came from, I'm inclined to go with Mills (and CEET's) value of 2 KWh/GB.





Looking at data usage, BTI's number (1.58GB/mo) looks far more reasonable, having been sourced from Verizon as the average for iPhone subscribers. Using Mills' data of 20 Exabytes of total bandwidth and 1.2B subscribers, you can independently come up with an average of 1.39GB/mo.  While I'm sure there are people using more than 10GB/mo as Mills suggests, this is clearly not a good representative value.





Using these selections to redo the calculations, we get:





Mills:  600 of the 700 KWh are from the wireless network, which should now be divided by 7.6, or 78KWh.  Adding back in the remaining 100KWh leaves us with 178KWh.  Note that this includes all embodied energy.





BTI:  Substituting 2 KWh/GB for 19 yields 38 KWh/year.  Adding the remaining 27 KWh/year yields 65 KWh/year.





Summary:  Unless you're personally over 5GB/mo of mobile data, feel free to hold off on your iPhone guilt trip for now.




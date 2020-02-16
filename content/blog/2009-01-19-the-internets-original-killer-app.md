---
author: nearwalden@gmail.com
date: 2009-01-19 21:08:18+00:00
draft: false
title: The Internet's Original "Killer App"
type: post
url: /2009/01/19/the-internets-original-killer-app/
categories:
- posts
---

The Sunday Times in London caused a big news splash a week or so ago with [their coverage of Physicist Alex Wissner-Gross' comments about the GHG emissions of Google searches](http://technology.timesonline.co.uk/tol/news/tech_and_web/article5489134.ece), which apparently turned out to not be Wissner-Gross' comments, and so on and so on.





But the story got our team thinking about the carbon impact of common internet activities, and wondering about the impact of each email, YouTube, iTune, SMS text, and tweet that flies across the net. We all have day jobs, so we couldn't estimate all of them, but we had some good internal data on email so Mark Monroe led the team in an analysis of the emissions of the internet's original (warning:  bad pun coming) "killer app".





We broke the email process up into 4 parts: composition, processing, and storage. This made the analysis easier and highlighted some big differences in where the carbon loads are.  The other big area to look at would be transport (the energy used by switches in the network to move the bits around).   That's the one area we didn't have good data, but the time involved in transit in the network is so small that we believe it is much lower than the storage or processing costs.  (anyone have any data?)





For processing, we looked at the energy consumed by one of our large enterprise email systems. This system serves over 12,000 employees, processing 12.6 million emails per week.  For all that work, we ended up estimating the energy per email processed at about 0.13 watt-hours, which in the US would average about 0.08 grams of COe2.









Storage was next. The same server farm has over 330 million emails stored, with an average size of 76KB and and average age of 18 month on disk. That's roughly 27,000 emails per employee, stored mostly on redundant, highly available spinning disks within the complex. When all was included, storing the average email used up another 0.36 watt-hours, or about 0.23 grams of CO2e.  With storage we're now up to 0.31 grams of CO2e.





On to composition. Looking at a random sample of about 62,000 emails, we found the median number of new characters typed into an email was around 300. If the average English word is 6 characters, and the average typing speed while composing is around 19 words per minute, our typical user is spending 2.6 minutes in front of a laptop, desktop, or thin client to compose each message. We estimated the average power draw for these 3 types of devices at our company is about 66 W, so the 2.6 min of composition time would consume about 2.9 watt-hours of energy, producing 1.8 grams of CO2e (obviously it would be less if you only used thin clients, more if you only used workstation-class PCs).





Note that that's six times the amount of energy and carbon produced in the processing and storage steps. But it highlights the fact that the back end email systems are pretty efficient. It's the time sitting in front of the console that chews up the big energy.  As an example, the 25 minutes it takes to compose this blog entry on my 32 watt laptop results in 8 grams of CO2e.  The same pattern probably holds for Google searches, where the 0.2 seconds the search spends inside Google's data center is nothing compared to the minute or two you spend reading it on your screen and clicking through to several references.





Add up the emissions to compose, process and store a message for 18 months and it totals 2.19 grams CO2e. To put this in perspective, humans emit 0.5 grams of CO2e per minutes by through breathing, so a 2.6 minute email is 1.3 grams of CO2e from breathing.  Doesn't seem like much until you consider the total volume of email is estimated at 97 billion messages per day, which turns our little puffs of CO2e into 212,000 metric Tons of CO2e per day.





If the amount of spam keeps rising, maybe this will be our "killer app"!




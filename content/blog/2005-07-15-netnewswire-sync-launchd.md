---
author: nearwalden@gmail.com
date: 2005-07-15 20:24:05+00:00
draft: false
title: NetNewsWire Sync, Launchd
type: post
url: /2005/07/15/netnewswire-sync-launchd/
categories:
- posts
---

I rebooted by desktop Mac today and suddenly I couldn't sync NetNewsWire from my laptop to my desktop (acting as ftp server) anymore.  I starated getting a "Connection Timeout" message where it was working prior to the reboot.





I realized that I had done a software update on the desktop (ftp server) to OS X 1.4.2.  Poking around I found that ftpd was no longer getting launched by xinetd, but had been migrated to launchd.  Reading up on launchd and searching the web, I found that the key "OnDemand" was set to TRUE (by default), causing the daemon to startup each time.  I also confirmed that the "Wait" key (now in inetdCompatibility) was set correctly to FALSE.  I added OnDemand, restarted my mac (I couldn't get launchctl to reload ftpd, so I finally gave up), and ftp is quick again, so that NetNewsWire sync works fine.





For reference, here's the new file in /System/Library/LaunchDaemons:  [ftp.plist]("./images/ftp.plist")









Technorati Tags:  

[netnewswire](//technorati.com/tag/netnewswire"), [mac](//technorati.com/tag/mac")









---
author: nearwalden@gmail.com
date: 2008-05-19 23:29:02+00:00
draft: false
title: OpenSolaris install
type: post
url: /2008/05/19/opensolaris-install/
categories:
- posts
---

Had some time to play around over the weekend with [OpenSolaris 200805 release](http://www.opensolaris.org/index.html).  It's a huge, huge step forward.  There's still some rough edges, but so far they've all been things that seem fixable in a relatively short amount of time.





One thing for people to be aware of is [a bug in the current release](http://bugs.opensolaris.org/view_bug.do?bug_id=6690194) that means that you can't install in partitions of certain sizes or locations on a multi-OS disk.  In my experience there's only two things that work:  1) you install OS in the first partition, in which case it can be any size, or 2) you install in a partition that's less than 4GB in size.  This isn't totally clear from the bug report linked above.





The other thing I'm having trouble with is running under [Virtual Box](http://virtualbox.org/) on my mac (btw, the latest VB release is wonderful - if you want multiple OS's on your system try VB first).  Can someone publish the right xorg.conf file to go full screen on the MacBook Pro?





Lastly, emacs IPS package, please?




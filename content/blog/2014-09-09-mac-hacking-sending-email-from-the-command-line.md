---
author: nearwalden@gmail.com
date: 2014-09-09 01:28:57+00:00
draft: false
title: 'Mac Hacking:  Sending Email From the Command Line'
type: post
url: /2014/09/08/mac-hacking-sending-email-from-the-command-line/
categories:
- posts
---

![header-cover](/images/2014/Sep/terminal-ifconfig.png)






In moving an automated process from a linux box over to a mac, I found myself missing cron's built-in ability to send an email as I switched over to OSX's launchd.  The obvious answer, sending an email from within my bash script, send me looking for an easy way to send an email from the command line, without needing to install sendmail or postfix.  Ideally I'd use Gmail as an SMTP service, but not a hard requirement.





A number of articles cited [_msmtp_](http://msmtp.sourceforge.net/doc/msmtp.html) as a good solution, and [this article](http://www.tuaw.com/2010/05/04/msmtp-a-free-tool-to-send-email-from-terminal/) provided a great overview of how to install it.  Furthermore, it supports Gmail and can use the OSX keyring for account info, which are nice.  However, in the 5 years since it was written, enough things had changed that I couldn't follow it directly.  Specifically:






  1. I ended up using Macports, since I was missing pkg-config (and probably other stuff) that would have let me build _msmtp_ from source.
  2. Thawte made some cert changes in 2010, and the described config doesn't work as written.




So here was my process:






  1. Installed _msmtp_ via Macports, including the _openssl_ variant ('_port install msmtp +openssl_').
  2. Installed the _curl-ca-bundle_ from Macports to replace Thawte.
  3. Created an  _msmtprc_ file as described in [the earlier instructions](http://msmtp.sourceforge.net/doc/msmtp.html), and store at /opt/local/msmtprc.  The only change is the location of the cert file, which should now be:





`tls_trust_file /opt/local/share/curl/curl-ca-bundle.crt`
  4. Manually added the account to the OSX keyring and added a .mailrc as described in [the earlier instructions](http://msmtp.sourceforge.net/doc/msmtp.html).




Works great!




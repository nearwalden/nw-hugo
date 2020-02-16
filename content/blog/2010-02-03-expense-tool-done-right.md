---
author: nearwalden@gmail.com
date: 2010-02-03 22:16:10+00:00
draft: false
title: Expense Tool Done Right
type: post
url: /2010/02/03/expense-tool-done-right/
categories:
- posts
tags:
- business
---

Yesterday I went looking for a simple tool to do expense tracking while I travel around, and found a great fit in [Xpenser](http://www.xpenser.com/). You can post expenses over IM, SMS, email and through the web.  When using email you can even attach a photo of the receipt, presumably taken with your phone.





All it expects is a text stream of the form "{activity} {amount} {tags}", such as "Dinner with Jim 46.80 projectx", which will (as you would hope) file an expense into the ProjectX report for $46.80 with the note "Dinner with Jim".





They also have an open API.  Since I needed to catch up on some expenses I decided that command-line entry would be easiest, so I whipped up this script (note: it doesn't deal with consecutive spaces correctly):




    
    <code>#!/bin/bash
    #
    # this script writes an expense to xpenser.com
    # change email address and password to match xpenser acct
    LOGIN="address@email.com:password"
    URLSTART="http://xpenser.com/api/simple/?q="
    URLEND="&format=json"
    Q=$1
    curl -i -u $LOGIN $URLSTART${Q// /+}$URLEND
    </code>





I named the command 'xpens', so now I just type **xpens "Dinner with Jim 46.80 projectx"** and I'm good!





Next, a search for a simple CRM app....




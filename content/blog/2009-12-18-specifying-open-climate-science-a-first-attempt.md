---
author: nearwalden@gmail.com
date: 2009-12-18 04:31:36+00:00
draft: false
title: 'Specifying Open Climate Science:  A First Attempt'
type: post
url: /2009/12/18/specifying-open-climate-science-a-first-attempt/
categories:
- posts
tags:
- climate
---

In [my last post](http://nearwalden.com/blog/?p=1176), I used lessons from the open source software community and the [Creative Commons](http://www.creativecommons.org/) effort explore what we mean by "open climate science".  In this post I'm going to take the next step and propose a specification for open climate science.  Finally, in the next installments I will look at the how to implement this specification using our current intellectual property legal framework.





Before I dive in, it is worth reiterating that I am not a scientist (and, by logical extension, not a climate scientist).  I have a lot of experience with open source through my job at Sun, and I believe that much it is applicable to this situation.  However, I'm sure there are subtleties that I will miss in this effort.  Hopefully, though, it is complete enough to help facilitate a broader discussion.





The first step is to define some terms that describe the process of climate science (I'm open to suggestions for these).  I'll use the following to describe the process itself:





<blockquote>
  
> 
> Climate science consists of running a _calculation_ across one or more _data sets_ and producing a _result data set_.  Scientific conclusions or observations are based on the _result data set_
> 
> 
</blockquote>





Beyond that we will also need some terms to help us talk about the mechanics of doing the science as described above:






  * Some data sets are a _raw_, meaning that they are taken directly from human or machine based observations.
  * A _calculation_ is done using an _algorithm_ that is embodied as _software_.  
  * _Software_ can exist in _source_ and _binary_ form (generally, _source code_ is the software humans write and can read, _binary code_ has been compiled into 1's and 0's that a computer understands)
  * The term _metadata_ will describe any additional information beyond the software and data sets which is required to understand or accurately recreate a result.  This includes the schema of the data (e.g. units of the numbers), required software tools or libraries, including version numbers, models and calibration of sensors, etc.  




The second step is be to identify the use cases that we'd like the concept of "open climate science" to support.  While _'use case'_ may sound benign, they are in fact the most critical part of this discussion.  If there isn't agreement whether these use cases embody the philosophy of 'open' that we are looking for, then the rest of the discussion is pointless.  So far I've been able to identify three main use cases:






  1. Allow others to reproduce and verify the result data set.   An example might be a scientist or other interested party who looks at a result and says "That surprises me.  I wonder if there's something funny in the data, or if they made a mistake in the code?"
  2. Allow others to run variations on the calculation.  For example, another scientist might want to run the a variation of the calculation on the same data sets in order to see what the impact is on the result.
  3. Allow others to combine some or all elements of the experiment with other elements and produce a different experiment.   For example, another scientist may want to take a calculation which measures the correlation of two data sets and apply it to a third data set to see if the resulting correlation is similar.




Some may say that use cases #2 and #3 could be difficult to tell apart in some situations, and they would be correct.  This is also a common issue in music and literature:  as many artists and authors "sample" other people's work, frequently the question arises whether the new work is just a variation on the earlier work, or is in fact a new work that is distinct of the earlier one.  Since copyright law distinguishes between these two cases, understanding where that line is may be important in these situations.  However, if we agree that both #2 and #3 are important aspects of open climate science, then defining the line between them becomes less important.





Its also important to note that we haven't yet talked about avoiding undesirable use cases.  For example, I'd rather not have someone take my results, write a paper about it and imply that they created the data themselves.  Or I may be upset if someone puts my result data sets on a CD and sells them to others.  These are important, and we will start the process of dealing with those below.





Finally, let's take the use cases and definitions above and write a proposed specification of open climate science.





For the purpose of reproducing results, running variations of the calculations, and creating derived calculations, the science is open if:






  1. All input data sets are _freely available_ and include all relevant metadata necessary to perform the desired calculations.
  2. All calculations are _freely available_ in source code form and include all relevant metadata necessary to execute the code as-is or make reasonable modifications.
  3. The results data set(s) are _freely available_ and include all relevant metadata.
  4. All necessary tools are either _freely available_ or _commercially available_




For the purpose of this specification, _freely available_ means that digital copies are available for download at no cost (copies on physical media may or may not be available, and may or may not be free).   _Commercially available_ means that it is available for sale, such as a specific computer or software package, but does not require that the cost be zero.





In order to protect the creators of the open science, we need to add some optional specifications which restrict the users.  These can be used at the discretion of the creator.






  1. All data sets and software are available under these terms for non-commercial use only.  These may or may not be available for commercial use, and other terms may apply.
  2. Any results published using the data sets and software under these terms must acknowledge the source of the assets which were used.




Another thing creators may want to do is control the permissions around derived works.  We'll look at that more closely in the legal discussion.





That completes the proposed specification.  Its not very long, but does ask a lot of the open climate scientist.





Before we move on to the next installment, there is one possible change which would strengthen this spec further, and that is to require that all input data sets are either a) raw and _freely available_, or b) _open_, using the above definition.  This means that no climate science is open until everything it depends upon is also open.  In the software world this is true, but I will leave it as a question whether that makes sense in the case of climate science as well.





In the next installment we'll use this specification and intellectual property law to create a license which can legally formalize this specification.




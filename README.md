# How Can [Lawyers on GitHub](https://github.com/dpp/lawyersongithub) Self-Organize Their Own Directory?

## Context

Good news: Thanks to [https://github.com/dpp](https://github.com/dpp) there is a [Lawyers on GitHub](https://github.com/dpp/lawyersongithub) directory!  Bad news: It remans unattended for long period of time and therefor does not function as an ongoing resource.  

## Fix

If a lot of lawyers on GitHub had the power to merge pull requests, we'd be in good shape because somebody would likely take a look in a timely manner and merge or otherwise manage the requests.  But how can a lot of people have the authorization to merge pull requests to add names of new lawyers on GitHub who seek to be included on the list here "[Index](https://github.com/dpp/lawyersongithub/blob/master/index.md)"? 

Simple answer is to include all user currently listed or with [pending pull requests](https://github.com/dpp/lawyersongithub/pulls) to be listed on "[Index](https://github.com/ComputationalLaw/lawyersongithub/blob/master/index.md)" to a [team](https://help.github.com/articles/creating-a-team/) with [rights to merge pull requests](https://help.github.com/articles/setting-up-teams/).  

## Problem with Fix

**But What if Jerks Add Themselves and Make Bad Future Requests?**

If a threshold is needed but nobody has time to police a community (this is a pretty normal set of constraints) then I recommend a small team (I volunteer is 2-3 or more others will hack with me) agree to meetup for a rapid hack session (Skype/Hangout/etc) to make an automated solution to automatically accept or reject pull requests based on a clear, machinable, relevant objective fact.  The fact needs to be programmatically accessible at an open API (these are the favorite kinds of facts for GitHub lawyers, right?) and then we can sit back and let the new lawyers flow in as their pull requests are automagically merged according to the application of a just, efficient, effective and measurable rule of computational law.  

The factor needed to establish a threshold for automatic merge of new lawyers should filter out the foreseeable problematic pull requests.  Leaving aside any issues of form/format issues (eg max character count, etc) I assume we'd be most concerned with filtering out trolls and other fly-by people who just hate lawyers on GitHub for some reason and seek to make nonsense or illegal (porn, threats, etc) contributions to the list.  What better factor to screen for lawyers on GitHub in good standing than how many commits over a reasonably long period of time that user has made on GitHub?!  

I found info and a few ways to grab that info programatically here:
* https://developer.github.com/v3/activity/feeds (eg:  https://github.com/dazzaji.atom)
* http://dcrec1.github.io/github-user-events (eg: http://dcrec1.github.io/github-user-events/#/dazzaji)
* https://github.com/blog/1360-introducing-contributions
* https://github.com/nuk/codemood/blob/master/lib/github_collector.rb

## What Next?

* **Ideal outcome**: the user who owns [dpp/lawyersongithub](https://github.com/dpp) and/or the user he has provided authorizations to help out (https://github.com/adelevie) takes the requested action (or maybe some other action to keep things moving).  

* **Suboptimal** (but fine) **outcome**: the users who own or help with the repo [dpp/lawyersongithub](https://github.com/dpp) decide they don't *really* have time/attention to curate this list and update the [index on the existing repo](https://github.com/dpp/lawyersongithub/blob/master/index.md) to point at the [correspondng file in the forked repo](https://github.com/ComputationalLaw/lawyersongithub/blob/master/index.md).  In this case, I'll take a turn at curating while seeking a person or group to pass it onward to on a longer term basis. 

* **Not Fine Outcome**: Continued piling up of pull requests or we have a temporary reduction of backlog followed by continued pile up of pull requests.  So... let's take a moment to hack a more endurng fix, ok?

## How Many Piled Up Pull Requests Are There?

As of now, the [pull requests](https://github.com/dpp/lawyersongithub/pulls) number **43 Open** and 64 Closed.  This is a repo that, all in all, is functioning and a great idea.  It's worth transforming from a good idea to a sustainable resource. 

Here is the pull request info as of now: 

Update index.md
#109 opened a day ago by dazzaji  
Add Firoz to the list
#108 opened 12 days ago by gioiello  
Adding myself to list
#107 opened 17 days ago by akinomeroglu  
Gary Grumbley added to member list
#106 opened 18 days ago by ggrumbley  
Create Michael Roberts
#105 opened 19 days ago by MikeRobertsIsHappy  
Adding Myself
#104 opened on Dec 21, 2016 by JurisHacker  
add Mark Oblad
#103 opened on Dec 16, 2016 by markoblad  
Update index.md
#102 opened on Nov 18, 2016 by DeltaCharlieAlpha  
Update index.md
#101 opened on Nov 2, 2016 by sdbedi  
Thomas Fleck asking to join this list
#100 opened on Oct 1, 2016 by fendi911  
add me, yo
#99 opened on Aug 29, 2016 by paultopia  
That's the right place for it
#98 opened on Aug 8, 2016 by oatsandsugar  
added my contact information
#96 opened on Aug 3, 2016 by bdscheiderer  
Add Adam Simon
#95 opened on Aug 2, 2016 by simon-adam  
Update index.md
#94 opened on Jun 27, 2016 by abueesp  
added Hans Kayaert
#93 opened on Jun 13, 2016 by HansKayaert  
Adding Lindsey Marchessault
#91 opened on Jun 1, 2016 by LindseyAM  
Adding Wilhelmina Randtke (Florida Bar) to list of lawyers on GitHub
#90 opened on May 23, 2016 by randtke  
adding @wabisabiyo to the list
#89 opened on Mar 26, 2016 by wabisabiyo  
Adding @allalala
#88 opened on Mar 25, 2016 by allalala  
Corrections of malformed markdown links
#86 opened on Mar 15, 2016 by jdelacueva  
Fix busted markdown link
#85 opened on Mar 15, 2016 by zeke  
Added tswise to index.md
#84 opened on Mar 1, 2016 by tswise  
Add Ansel Halliburton
#83 opened on Dec 8, 2015 by anseljh  
 1
added myself
#82 opened on Nov 13, 2015 by thenerdlawyer  
Update index.md with Mark Oblad
#81 opened on Sep 14, 2015 by markoblad  
Update index.md
#80 opened on Jul 25, 2015 by SHenriquez  
Update index.md
#79 opened on Jun 11, 2015 by FreemanLaw  
Update index.md
#78 opened on Jun 9, 2015 by antonejohnson  
Remove extraneous control character
#77 opened on May 26, 2015 by kemitchell  
 1
Add Judson Mitchell
#76 opened on May 26, 2015 by judsonmitchell  
Make data more machine-readable
#75 opened on May 21, 2015 by benbalter  
 8
Update index.md
#73 opened on May 11, 2015 by mwweinberg  
Add Sam Glover
#72 opened on Apr 9, 2015 by samglover  
Update index.md
#71 opened on Apr 7, 2015 by batemapf  
Add v dave z to 18F
#65 opened on Jan 20, 2015 by adelevie  
 1
Update index.md
#61 opened on Dec 11, 2014 by HazardJ  
 6
Update index.md with info for Justin La
#60 opened on Dec 2, 2014 by jlasoul  
move palley and pipkin from "in gh" to "on gh"
#51 opened on Jun 13, 2014 by sdpalley  
 1
Update index.md
#47 opened on Jun 3, 2014 by prestonjbyrne  
Add my info
#45 opened on May 8, 2014 by cristobol  
Corrected placement of my information.
#41 opened on Apr 29, 2014 by dereklipkin  
Patch 1
#32 opened on Apr 2, 2014 by randtke  




---------------------------

Prior README.md

# Lawyers on GitHub

A club full of lawyers who also have GitHub accounts.
All you have to do to join is create a [pull request](https://github.com/dpp/lawyersongithub) with
information about your bar membership.

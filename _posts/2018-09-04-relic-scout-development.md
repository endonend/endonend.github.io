---
layout: post
title: "Relic Scout Development Journal (S1E2): Hit List"
microblog: false
audio: 
date: 2018-09-03 21:44:16 -0400
guid: http://endonend.micro.blog/2018/09/04/relic-scout-development.html
---
As I mentioned in my <a href="https://www.endonend.org/2018/08/21/relic-scout-development-journal-s1e1-kickoff/">last Relic Scout post</a>, I am going to document my progress with launching new features on the site.

Today I tackled some design decisions related to the &#8220;Hit List,&#8221; which is a new view we are adding to Relic Scout. This view will include (to start) all graded comic book auctions ending in the next 24 hours that have at least 1 bid.

In addition, we will be adding Relic Scout information &amp; tools like:

<ul>
<li>a link to other listings for the specific issue</li>
<li>historical sales &amp; price trends</li>
<li>a deal score rating which gives a simpler metric to judge the current auction price versus historical trends</li>
<li>the ability to bookmark individual listings for later</li>
</ul>

Here&#8217;s the latest mockup of what we&#8217;re going for:

<img src="http://endonend.micro.blog/uploads/2018/f863ca0e9d.jpg" alt="Hit List" title="Hit List.jpg" border="0" width="500" />

I took a couple cues from RSS reeders (stars and &#8216;mark all as viewed&#8217;) as I thought those were useful tools to deal with large amounts of constantly refreshing information.

One element I need to work on is the &#8216;deal score&#8217; area. I want to find a way to surface small amounts of useful historical pricing information, something along the lines of 7-day, 30-day, and all-time prices maybe? Modal or tooltip is the obvious answer, though I want them to work well for mobile users.

We could also add global user-level settings for grading service, grade range, and deal score minimum, which could be useful for these types of pages.

Any feedback would be greatly appreciated &#8211; especially from comic book collectors and frequent eBay users.

In my next post I&#8217;ll share the final design mockup and then, later, I&#8217;ll share a link to the live page on <a href="https://relicscout.com">relicscout.com</a>.

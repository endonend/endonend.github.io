---
layout: post
title: "Tales from the Relic Scout Launch"
microblog: false
audio: 
photo: http://blog.relicscout.com/wp-content/uploads/2014/03/relic-scout-beta.jpg
date: 2014-03-29 19:00:00 -0500
guid: http://endonend.micro.blog/2014/03/30/tales-from-the.html
---
A little over a year ago, I founded <a href="http://ekowave.com">Eko Wave</a> with two friends (who also happen to be co-workers at the real job.) Last week, almost a year later, <a href="http://blog.relicscout.com/2014/03/beta/">we launched our first product</a> called <a href="http://relicscout.com">Relic Scout</a>.</p>

Relic Scout is a utility for collectors with two primary purposes:

<ol>
<li>Keep track of your want list.</li>
<li>Find the best deals on these items, so you can maximize your budget and buy even more for your money.</li>
</ol>

<img src="http://blog.relicscout.com/wp-content/uploads/2014/03/relic-scout-beta.jpg" alt="Relic Scout Beta" title="" />

We take your want list, entered on RelicScout.com, and use that information to find buying options for you to consider. Then, each day, we’ll update the site with new options for each item, as well as keep track of auction status (on an hourly basis to start), so you have updated information available to make decisions. Then, you’ll be able to buy with confidence when the right eBay listing comes up for your item (or elsewhere, like a garage sale or flea market.)

Relic Scout has built-in support for Comics, Sports Cards, Sports Memorabilia, Coins &amp; Currency, and Trading Card Games. We also have an 'Other' category, which has basic support for many of the most popular collectible categories on eBay.  If any of this sounds useful or interesting to you, please head over and <a href="http://relicscout.com">sign up</a>!

With the elevator pitch out of the way, I'd like to share some behind-the-scenes detail as it was a very valuable learning experience.

<h3 id="ideas">Ideas</h3>

Over the last year, we had numerous ideas on where to take Relic Scout. We worked on many of these in some fashion, but most of them either evolved into other ideas or were dropped all together. In the end, we scaled the original idea back with the intention to launch what we considered a minimum viable product. Something we would find useful, even if it wasn't fully built out or realized yet.

I highly recommend this approach to anyone looking to build a product or launch a business. Start with the basics, launch, and then evolve as fast as possible once you get feedback. It's really important to get <em>something</em> out there in the real world as quickly and cheaply as possible. It doesn't have to be perfect either. (Remember my post, <a href="http://endonend.org/posts/make-do-and-wabi-sabi">Make, Do and Wabi-sabi</a>?)

Keeping the idea/project moving forward has a few benefits:

<ul>
<li>It keeps you from second guessing decisions</li>
<li>It gets your idea out in the wild faster, so you can start gaining feedback to build the second, third or even fourth release. You know the ones that have a much better chance at succeeding?</li>
<li>It separates you from every other person that has ideas, but doesn't execute</li>
</ul>

<h3 id="execution">Execution</h3>

With all those idea changes/adjustments going on, we also considered many approaches to executing the idea. Last Spring I built a proof of concept in PHP -- a basic script that queried eBay for an item, parsed out the data, and organized it in a MySQL database. The idea of custom building an entire site seemed daunting at that point, so we looked elsewhere.

Then during early Summer, we took a look at building it on top of WordPress, as we came across a case study on a company that built a <a href="http://en.wikipedia.org/wiki/Software_as_a_service">SAAS</a> product on top of WordPress. As flexible as WordPress can be, we decided it would take too much hacking to break away from the CMS/blog nature of the software.

That brings us to late Summer/early Fall, where we took a look at a much more flexible CMS system, Expression Engine. We actually made a lot of progress on that site. With some dedicated effort we could have pushed that across the goal line, I'm sure. But that too felt like a big pile of hacks, that could easily unravel with future changes in the platform. So in December, we decided to take a break from the Expression Engine site and re-evaluate.

After the holidays I started hacking with Ruby on Rails, a programming language I've always wanted to learn, but in the past I didn't have a good idea to use in my learning process. So I just started. Low and behold the development started moving <em>really</em> fast and three months later, Relic Scout was released to the public in it's current beta state.

The takeaways from this part of the project:

<ul>
<li>If you want to learn a programming language, I highly recommend having an idea of what you want to build. Having that idea helps keep you motivated and interested, rather than just following some tutorial you find online where you learn to build something you'd never really use.</li>
<li>There is serious allure in building on top of another system to get you started. I firmly believe now that unless your project is meant for that system, build your own -- especially if you have any programming experience or have a goal to learn a language. For example, unless your project is a blog or heavily involves content, it's probably not a good idea to build it on top of WordPress.</li>
<li>If you have an idea you believe in, never give up. It would have been easy to give up and say I don't know how to program well enough to build what I want, but I think in many cases you'll surprise yourself in how much easier some paths actually are, compared to the apprehension you feel before you start.</li>
<li>Building something that's a little complex, takes you outside your comfort zone, teaches you a ton, and ends up fairly close to your idea (from scratch, no less) is amazing. If you have the itch to build, definitely scratch it.</li>
</ul>

<h3 id="launch">Launch</h3>

Launching the site last week was exhilarating and tiring.  It was so exciting to be able to take the site live and show people we know and care about where all that time and hard work went over the last few months. It was also very nerve wracking. Stress about the site not working or no one caring, or worse, thinking it sucks all hit you hard. You work so hard to get to that point, you don't want anything to take that good feeling of launching away.

Now is the time to be patient. Or at least that's what I tell myself. Since launch, we'e had over 90 unique visitors hit the site and around 11 signups. On the positive side, that's a 10%+ conversion rate, but it's also way less traffic than I had hoped for, given that all three of us know way more than 90 people in total.

So next up for us is a push to get to 50 users this month. We're going to start publishing more on the Relic Scout blog, hitting up social media to start building relationships with potential users, and what ever else we can dream up to help kick the site usage into high gear. At this point, users means more feedback, which means we improve the site faster.

I am starting to think the hardest part of this entire project wasn't learning a new programming language and coding the site from scratch or the process it took to get to that point, but what we have in front of us. It's an exciting challenge at least.

Stay tuned!

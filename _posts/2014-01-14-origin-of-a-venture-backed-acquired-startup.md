---
title: "Origin Story of a Venture-Backed, Acquired Startup"

layout: post
categories: "public"
excerpt: "For the past 18 months, my 3 co-founders and I had worked out of my brother's cold cold basement, without pay or insurance. We'd built a handful of products that hadn't gone anywhere. Our future wasn't bright."
location: "San Francisco, CA"
---

# [{{ page.title }}]({{ page.url }})

Decide.com was acquired by eBay on September 6, 2013. For those unfamiliar with Decide, we invented technology that predicted the future price of consumer goods. Thinking about buying a Samsung television? We'd tell you whether the price would drop in the next two weeks. We helped you decide when to buy.

Seattle, Late 2009 &mdash; For the past 18 months, my 3 co-founders and I had worked out of my brother's cold cold basement, without pay or insurance. We'd built a handful of products that hadn't gone anywhere. Our future wasn't bright.

## An Observation 

Brian noticed his girlfriend (now wife) Jessica, had looked at the same dress on Nordstrom's website several days in a row.

Brian: "Why do you go to that page every day?"<br>
Jessica: "I'm waiting for the price to go down"<br>
Brian: "Oh, we can build you something that checks it for you"

## A Prototype 

Brian told Ian about the conversation and by the following Monday they'd built a prototype. They showed it to Hsu Han and I  during our weekly meeting on my brother's couch. Without thinking about the normal startup criteria like market size, defensibility, differentiation (it would've failed all of them), we hopped in. It sounded like fun.

The prototype was simple, you entered a link to something you wanted to track, it would check the price every day and email you when the price changed.

It needed a little work though. Their initial prototype was a white page, a logo and a input box. Like Google. Missing were the customary one sentence value proposition and information on how it worked.

After taking 9 months to release our first product, we made a rule that any new product had to ship the following Monday. Regardless of how buggy, unpolished and how many features it lacked.

We renamed it PriceYeti (is it the right price yet?), made some small improvements and got it out the door.

Here's what it looked:

<a href="https://s3.amazonaws.com/hsukenooi/homepage_step1.png" target="_blank" class="image-link">
  <img src="https://s3.amazonaws.com/hsukenooi/homepage_step1.png" width="570">
</a>

## Cutting Corners 

To adhere to our "it must ship in one week" rule, we got good at cutting corners. For this project, we decided to not invest in the scraper despite its importance. Accurately tracking the price of a product was what the site was about. It'd be terrible to send an email, notifying someone that the price of something they wanted had dropped, only to have them find out it hadn't. Over-promising and under-delivering is typically a bad user experience.

Unfortunately, building an accurate scraper that would work on any site would've taken weeks if not months. It would also require constant maintenance since websites are constant changing. It would've been a huge investment. We needed to know if this was something people wanted first.

The fastest way to write software is to be the software.

Instead we made a decent scraper and had users verify the current price. When the scraper detected a price change, rather than emailing the user automatically, it published the change to an internal dashboard. We (mostly Ian, thanks Ian) would check the dashboard several times a day, verify the price changes and send  the emails by hand. It's not a scalable solution but it got us moving immediately.

## When a Bug Isn't a Bug 

For most sites our semi-automatic system worked. Someone would track a product from Costco's website. We'd diligently check the dashboard for price changes, verify and send out the email.

It didn't work that well for Amazon though. The system would detect a price drop from $500 to $450 but when we manually verified the price it would be $475. We thought there was bug but couldn't find it. To help us troubleshoot we had the scraper save the page when it detected a price change. That way we could see the same page the scraper saw. If the scraper said $450 but the price on the page was $475 we'd know there was something wrong on our end.

## That's Interesting.. 

The scraper wasn't wrong. When we manually looked at the page, the price was in fact $450. What's going on?

Turns out in the few hours between the scraper detecing the price change and one of us manually verifying it, the price had changed again. The reason it was almost exclusively an Amazon problem was because their prices changed the most frequently.

We had no idea prices moved so often. We started collecting prices more frequently and graphing them over weeks. We found that prices even went up sometimes. We'd assumed, like most consumers, that prices either stayed constant or slowly declined as new products came out.

It was becoming apparent that when you bought something, not just what and where, was important. You could get the same product for significantly less, if you bought at the right time. If only there was a way to predict whether prices were going to go up or down.

## It's Good to Be Lucky 

We'd met Oren Etzioni 2 years earlier while Ian was a student in one of his Computer Science classes at the University of Washington. He'd politely told us the idea we were working on at the time, data mining resumes, wouldn't work. It'd only be useful if you have hundreds of thousands of resumes. How are you going to convince people to give your resume until then? Classic chicken or the egg problem.

2 years later, we were sitting in his office again. Telling him  he'd been right but we'd found something else he'd be interested in. We showed him what we'd learned, that prices changed often, that people could save money if they bought at the right time, that we'd been wondering if it was predictable.

We couldn't have found a better person to talk to about what we'd learned. Besides being  a Computer Science Professor specializing in Artificial Intelligence, Oren was a startup founder. His last startup (Farecast) predicted the price of airline tickets, was acquired by Microsoft and became Bing Travel.

I can't overstate how fortuitous this was. The only person who'd started and sold a consumer product based on predicting the price of something happened to be in Seattle and we happened to have taken classes from him.

He thought our findings were interesting. As he liked to say "I've seen this movie before." But first he wanted more data. Specifically answers to the following questions:

1. Does  price volatility happen in many categories?
2. Are the price changes meaningful?
3. Are they reasonably predictable?

We spent the next few weeks gathering data to answer those questions. I've never been to graduate school but I imagine it felt a little bit like that. Checking in with a professor every few weeks, presenting your findings. Fortunately the answer to all 3 questions was yes. As we progressed, Oren joined as the 5th co-founder and the rest, as they say, is history.

## Big Ideas Start Small 

If you're gonna take anything away from this story maybe it's that big ideas start small. The idea that led to Decide was price alerts. A feature most shopping sites have. Not a change the world, kind've big idea.

And that's okay.  I see people try to brainstorm their way into the next big idea. Like you can sit down one day, decide you're going to come up with the next big idea and will it into your consciousness. That's not how ideas work.

> You see, I think he better than anyone understood that while ideas ultimately can be so powerful, they begin as fragile, barely formed thoughts, so easily missed, so easily compromised, so easily just squished. <br><br>– Jony Ive on Steve Jobs

We wouldn't have stumbled into price predictions for consumer products unless we'd built a website about tracking prices. Sometimes jumping down the rabbit hole is the only way to see how deep it goes. Most of the time won't go very far but every once in a while you'll find an entire world.


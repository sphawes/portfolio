---
layout: post
title: The Onion of Tolerance
permalink: /onion-of-tolerance/
---

Throughout the course of LumenPnP development, I've adopted a product development methodology I call *The Onion of Tolerance* that has worked really well for us so far.

### ...what? An onion?

When you first put something out the door, the people that will give it a chance are **early adopters**. They generally understand that it's an early-stage product, and that there are going to be some rough edges. They have a high tolerance, sometimes surprisingly so. They're involved because they're excited about what you're doing, and they want to be part of it.

You're going to get a lot of feedback. They might be tolerant, but they're still human. They care about what you're building, and they want it to get better, so you're going to hear about a lot of stuff that sucks about your product, which is *great*. The real challenge comes when deciding *which order to fix the issues in*.

Your early adopters are the very center of the Onion of Tolerance, the unwavering unshakable core that will put up with an absurdly frustrating and finicky experience. The next, larger layer of the onion is *slightly* less tolerant of a bad experience, and there's more people in that layer. The layers continue.

I posit that **the next thing you should fix or add to your product should unlock the next-biggest layer in the Onion as a potential customer**. Fix the problems that keep *them* from engaging, then move on to the next layer.

### Why do it this way?

This approach has a lot of benefits. Every time you fix a batch of problems and move to the next layer, you unlock a whole new category of customers, helping the organization grow or increase runway. This is fantastic for cashflow if you are bootstrapped, and a steady increase in revenue looks great on your P&L.

It also manages expectations really well. You're never overpromising, always just selling your product to the people who are truly excited to exchange money for the amount of "done" it currently is. As a fledgling startup, you draw a fine line. You want to get your product into peoples' hands, make sales, and keep the company alive. But you also don't want to overpromise and give it to somebody that is looking for a more plug-and-play experience, and have the customer be frustrated. This whole thing only works if you're comfortable saying to a potential customer, "it's not ready for you yet."

Typically the problems you're solving to get to each new layer of the onion are the biggest, most annoying issues shared by the majority of your *existing* users. This means existing users are constantly having their largest frustration fixed, which shows solid and consistent progress on making the product better. Showing your userbase that you're listening to and acting upon their feedback is one of the best things you can do to help your community grow.

### How to do it

#### Determine what sucks

There are two main ways that we've used to find out what sucks about something: customer interviews, and dogfooding.

By conducting customer interviews, you're getting right to the heart of the matter. Don't choose folks that seem to be having a good time with your product. Pick the folks that are upset. Pick the folks that write you a novel about all the things that frustrate them. These are the perfect people to talk to. Praise is a good indicator of things to keep, but the negative feedback is orders of magnitude more valuable. The more critical, the better.

This does absolutely suck to do, to be fair. I think that's why many companies don't do these interviews, instead assuming they know what the customer wants. Spending an hour listening to why your decisions are bad and how this thing you built absolutely sucks is not fun. But it's the most important thing you can do to make it better.

I also recommend getting on the phone or a video call with a customer and letting them just talk, instead of only sending a survey. Surveys can be great for some A/B decisions, and even as a way of finding frustrated customers that you then reach out to for a call. But if every one of your customers is having an issue you aren't even aware of, and there isnt a spot on the survey to convey it, you're loosing that signal. You don't know what you're looking for yet, so it's best to just let them talk.

Another, less effective way is to [dogfood](https://en.wikipedia.org/wiki/Eating_your_own_dog_food) your product (or, using it yourself). The idea is to tighten the feedback loop between creator and consumer, making it so that fewer bugs are introduced and issues are fixed quicker, because you're your own user.

This is a great technique, and I think dogfooding also says a ton about the confidence your company has in the product, but you will ***always*** view your product with a bias. It's yours. You designed it. Your ego, emotions, effort, and sacrifices went into making it. You will ***always*** view it in a different light than a customer. You will make excuses for it that a customer will not. This isn't a reason to *not* dogfood. It's just never going to give you the full picture.

#### Order them

After a ton of customer interviews and your own experience using your product, you should have a list of stuff that sucks. Now you need to order them in the order you will fix them.

Critically, the rank is **not based on how much they suck**, but instead **the next layer of the onion**. Often, these are the same thing, but sometimes they differ slightly. The idea is to open up the product to the next layer of the onion, while also trying to reduce net suck for everyone. What's going to allow more folks to use it successfully? Who is the next-most tolerant group of potential customers? What feature or bugfix will unlock the next wave of sales that propel you to the subsequent layer?

The other main variable in determining the order is the difficulty of each item on the list. Rating "suck" on a scale from 1-10, 10 being the worst, a relatively easy 6 should ship way before a complex 10. Of course, the 10 is way more important and greatly reduces the total suck, but it shouldn't gate that 6 from shipping much sooner.

#### Fix them

Now, fix them relentlessly.

With each item on the list, you'll have a ton of feedback about *why* it sucks, and also probably a lot of suggestions about *how* to fix it. In general, you should take the fact that something is bad as gospel truth, but don't put too much weight in the suggestions on how to fix it. Bill Hader has an excellent quote about this in regards to writing:

<iframe width="560" height="315" src="https://www.youtube.com/embed/NHHZSNw9J2o?si=nhMG37p6KZvZ1iCO&amp;start=27" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Your customers might have some *excellent* ideas about how to fix the problem, and you certainly shouldn't disregard their suggestions. But they likely don't have the context on the product (and the company) to know the best solution. The solve should come when looking at the entire scope of the product, company, and even future products in development.

### What we did

Opulo followed this system for the LumenPnP. We got our first version of the machine (a kit) out the door to early adopters, and did a ton of customer interviews. We got three *incredibly* strong signals from those interviews, which we ranked:

1. It's a pain putting the machine together
2. Strip feeders are finicky
3. OpenPnP is difficult to use

Again, this rank is *not* how much each of these things suck. It's the most logical order to solve them for the next-most tolerant shell of the onion.

The signals we got from those interviews (and many more afterwards) have informed every single release we've done since. We immediately switched to an almost fully assembled version of the machine, solving issue one. Next, we designed and shipped component feeders, solving problem two. We're working on number three right now.

This has resulted in a consistent, steady increase in sales and general perception of the machine.

### Notes

**What if I rasied VC money?**

If you have a *ton* of cash, you don't need to worry about this tier system of incremental improvement. You can just tackle the whole onion at once. You should still be doing customer interviews and ranking the suck of each issue, but you can parallelize better and fix more of them simultaneously. This system is meant for a profitable, cash-flow dependent startup company.

**What's the last shell?**

The last shell of the onion isn't the general consumer market, although they're the second-to-last! The last shell is reviewers. These folks are the most picky, as they should be. It's their job to be the most aware and critical of their experience using a product, so that they can inform people about things that might be frustrating for them.

Given that they're the absolute last shell, you should only reach out to them when you've arrived at the last tier (or shortly before). The internet is written in ink, so if you're going to send a unit out for review, you better be pretty damn sure it's going to be a good review.

**But it's hard to fix hardware bugs!**

That's super true. Depending on how you manage your hardware production, "patches" are much more difficult. The LumenPnP is accessible and modular by design, so upgrade kits are very easy to manifest, allowing previous customers to enjoy the benefits of modern designs.

But an injection molded product with adhesives and heat stakes is not quite so editable. What you ship is more or less permanent. I'd imagine that much of this onion philosophy would occur on a longer timeline for those products, given that small, incremental improvements might be less feasible and a full new product release might be necessary to get to each new layer of the onion.

**This is dumb.**

Fair! I wrote this in the [imperative mood](https://en.wikipedia.org/wiki/Imperative_mood), but I'm certainly not trying to prescribe that everyone does things this way. It has some problems! What if a pithy feature opens up the next layer of your onion, but leaves your existing users to deal with a really frustrating problem? That sucks! What if the next layer of the onion is unlocked by a four-year R&D saga that you absolutely don't have the runway for? You have do something else. This is a **tool**, not a **rule**. It shouldn't be followed all the time, but instead only when it's useful.

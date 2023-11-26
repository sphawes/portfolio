---
layout: page
title: Opulo
permalink: /opulo/
---

In 2019, I did a Kickstarter for a project I called the Glowtie, a light-up bowtie you control using Wifi. I ended up spending nights and weekends soldering literally thousands of electrical components by hand. 3D printing and finishing the plastic parts in the build took hours and was hard to manage. In the end I made them all, but the whole experience was quite discouraging. It’s a huge pain and time commitment to make a product at small scale, and I wanted to find a better way.

![](/assets/glowtie/v0.2-hero.jpeg)

I looked into having boards assembled for me at board shops domestic and overseas, but was put off by the high-cost per part, and unfortunate anecdotes from friends struggling to manage production from afar. I also looked into purchasing my own Pick and Place (a machine that places the components on the bare PCB for you), but was met with price tags upwards of $100K USD. Instead, I decided to build the LumenPnP.

![](/assets/opulo/3_1.png)

The LumenPnP is an open source pick and place machine. This is the first machine I’m building to help enable [mid-scale manufacturing](/level-2-manufacturing/) for folks looking to start moving their prototype into production. By automating the PCB assembly process at home or at your business, you can greatly reduce the cost for smaller runs of product, and you can own the manufacturing process yourself, ensuring things are created to spec and to your standards.

I started prototyping in early 2020, and since then have been making YouTube videos about the R&D process. The project garnered some solid interest through YouTube, amassing 40k+ subscribers on the channel and 4k members in the Discord server.

![](/assets/opulo/hackaday.png)
*Hackaday article about the LumenPnP*

In December 2020, I quit my job at Formlabs and moved to Pittsburgh where I planned to bring the LumenPnP to market through bootstrapping.

![](/assets/opulo/cake.jpg)
*Going away cake from my team at Formlabs "We hope you fail and have to come back"*

Shortly after, I was contacted by an angel investor about raising money for the project. After officially founding Opulo in April of 2021, I took on the angel investment and continued work with my buddy Lucian on board.

![](/assets/opulo/lucian-garage.jpg)
*Lucian provisioning some laptops in my garage*

After almost dying from carbon monoxide posioning trying to heat my garage with propane heaters, we finally decided to get an office space.

![](/assets/opulo/office.jpg)
*The office shortly after moving in. It won't be empty for long!*

<iframe class="video" src="https://www.youtube.com/embed/e_WSFvBg8EU" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

On February 12th 2022 we launched the first version of the LumenPnP, which came as a kit. We sold out of our first hundred machines in under an hour.

![](/assets/opulo/launch-battlestation.jpg)

After shipping, I conducted dozens of customer interviews about the experience of setting up and using the LumenPnP. Three main signals arose:

1. Building the machine is a pain and takes too long for someone that's looking to purchase a tool, not a project.
2. Strip feeders, which are small 3D prints that hold electronic component tape for the nozzle to pick, suck, and require frequent human intervention. Folks wanted fully-automatic feeders that let you run your machine for thousands of pick cycles without the need for component reloads.
3. The software used to control the LumenPnP called OpenPnP, is difficult to learn and use.

We had our marching orders.

Just a few months later, we started shipping a semi-assembled version of the machine. Instead of taking two full weekends to print parts, solder components, and bolt everything together, this new version went from the box to built in under an hour. Issue #1 was solved.

![](/assets/opulo/printers.jpg)
*3D printer farm we set up to print all the parts for semi-assembled machines*

Next was powered feeders. This would prove to be quite a bit more difficult than shipping assembled machines.

I had been prototyping powered feeder designs since early 2020, but nothing had checked every box in the PRD. I wiped the slate clean and started from scratch, incorporating everything I had learned over dozens of prototypes.

![](/assets/opulo/feeder-proto-spool.jpg)
*One of the early prototypes of the LumenPnP Feeder*

We did tons of lifetime, validation, and beta testing on the design. And in April 2023, we began shipping feeders.

<iframe class="video" src="https://www.youtube.com/embed/Aq1uLzec1Ro" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

Launch went great, and we had our work cut out for us in keeping up with demand.

![](/assets/opulo/shipping-feeders.jpg)
*Dropping off the first batch of feeders at UPS*

Item #2: Check. Last is software.

OpenPnP is a great Swiss Army Knife. It can be adapted to almost any machine, and provides configuration options for the most niche types of hardware. But we're only shipping one. The vast array of settings, tabs, sections, and data fields is intimidating and confusing for folks who just want to use their machine.

We're starting to solve this one by making our [documentation](https://docs.opulo.io/) **exceptional**.

![](/assets/opulo/docs.png)
*Nozzle offset calibration page from our docs*

If we can help folks navigate calibration and setup of their machine and avoid the settings that aren't relevant to their hardware, it'll make the experience much smoother.

<hr>

As of this writing, Opulo is eight people strong. I'm incredibly proud of the team, and what we've been able to accomplish in just a few short years. And we're just getting started.

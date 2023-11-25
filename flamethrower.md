---
layout: page
title: Wrist-Mounted Flamethrower
permalink: /flamethrower/
---

Alright, here it is. The culmination of 8 years of messing with fire in the garage. My third and final (?) pass at a wrist-mounted flamethrower!

![](/assets/ft1.jpg)
![](/assets/ft2.png)

This thing is crazy dangerous, and crazy fun.

After my last backpack-based version I brought to New York Maker Faire 2014, I had a laundry-list of changes I wanted to make. The whole thing was controlled using a knock-off Arduino Uno with header pins gracefully hot glued into their headers, a perfboard abomination on my forearm for control, and a lead-acid battery (no I'm not kidding) attached to the already heavy aluminum backpack. Oof.

Since then, I've learned a tremendous amount more about how to make things, so things get less sketchy from here on out. This version does away with the entire backpack (and yes, the lead acid battery as well), instead favoring an approach where everything is mounted on my right arm. My method for analog gas control gets more reliable, and a custom PCB controls the whole shebang.

After doing some prototyping and testing with gas flow, I started fabricating the exo-skeleton-esque frame to hold all the components. I did all the CAD in Fusion360, sliced the 3D printed parts in Lulzbot Cura, and printed them on a Taz 5 with the stock extruder in Verbatim black PLA.

<iframe class="video" src="https://www.youtube.com/embed/wXYVUBZqZuk" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

After I had something to mount everything to, I started work on the PCB. The board had to control the servo for analog gas control, the solenoid valve, the taser for ignition, read inputs from the control switch on my hand, plus an OLED and a few buttons for mode selection. I went with a Atmel 32u4 for the Arduino IDE compatibility, relatively low cost, and native USB support.

<iframe class="video" src="https://www.youtube.com/embed/nJoeJ7d_UbU" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

The result is beyond satisfying. And bringing this crazy thing to New York Maker Faire 2018 was even more so. The NYC Fire Marshals responsible for making sure I didn't kill anyone or myself were beyond cool. Thanks Bob and Rob!

<iframe class="video" src="https://www.youtube.com/embed/A_SFpVtnvXI" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

Not sure if I'll ever dive back into the flamethrower game, but if I do, I'll probably make a custom tank so I can dump the whole thing at once for a HUGE burst, and redo the palm piece. I might replace the taser for some nichrome wire or a pilot light as the taser was fairly unreliable.
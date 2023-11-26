---
layout: page
title: Atlas Arm
permalink: /atlas/
---

The Atlas Arm is a prosthetic hand design that I worked on throughout my junior and senior years of college. I raised over $14k in funding, was invited to a [startup incubator program](https://innovationquest.uconn.edu/), and was awarded lab space to pursue the project.

![](/assets/atlas/testing.gif)

Prosthetic devices are expensive for two reasons: they are custom, and they require a lot of capital to get approved for usage through the FDA (or other relevant organization depending on your country). This project was an effort to solve the former. With modern CAD programs and additive manufacturing, custom prosthetics don't need to require lots of time to fabricate, using expensive methods.

The core of this project is a parametric script that I wrote that takes seven key measurements of an amputee's remaining hand, and extrapolates them out into a fully-operational prosthetic device that can be printed within minutes.

![](/assets/atlas/cad.gif)
*Generated CAD model based on measurements of my arm*

From there, it was fabricating the hand. Using a 3D printer with a dual extruder, I was able to print a single part that has both flexible and rigid components. This means that the fingers' hinges are built-in, and automatically return to an open position when not being actuated.

![](/assets/atlas/finger-test.gif)
*One of the first prototypes of the dual-material fingers*

This approach kept things tidy and strong, so I moved forward with fabricating a full hand with this method.

![](/assets/atlas/first-movement.gif)

I designed a base module at the wrist that had the microcontroller and pinout to the hand to control the device.

![](/assets/atlas/core-guts.JPG)

However, the prosthesis had to actually integrate with an amputee. This required electromyography (EMG), or muscle control, and a custom socket to fit an amputee's residual limb.

To ensure it fit the amputee I was working with, I 3D scanned the amputee's residual limb and designed a socket based on this scan.

![](/assets/atlas/socket.JPG)

Then, I needed to program the arm to react to an EMG signal. Three probes are placed in certain locations on a muscle, and tensing that muscle comes through as a signal.

![](/assets/squeezeTest.gif)

This project was a fantastic exercise in UX, engineering, and working through the bureaucracy of running a medical study at a university.

![](/assets/atlas/hero.jpeg)

<iframe class="video" src="https://www.youtube.com/embed/Lv9bJVDIcAg" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

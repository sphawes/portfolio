---
layout: post
title: OSHW Licensing
permalink: /oshw-licensing/
---

The LumenPnP has been fully licensed with GNU GPLv3 for its entire existence. I’d like to change this license, to make it more usable and free for others to use.

GNU GPLv3 is what’s known as a “viral” license, where anything it touches is forced to adopt the same license. This forces anyone to also fully open their entire design, otherwise it’s not for them. That’s actually quite restrictive!

Our licensing should be based on the reasoning behind why the LumenPnP is open source: because it’s a net benefit to users, builders, and the design. Forcing someone else to open the entirety of their project doesn’t accomplish that goal. If anything, it means folks might be hesitant to use what we’ve built. There’s nothing wrong with keeping your source closed if that’s what you’ve chosen, so we shouldn’t be punishing folks for making that decision.

I propose that all Opulo hardware source switches to a **weakly reciprocal** format for licensing, instead of **strongly reciprocal** one. This ensures that any improvements to our source make their way back to us, but we’re not forcing anyone into adopting our open ethos. The design benefits from being open, and users benefit from being able to use it for what they want to build.

The licenses I have chosen for this are as follows:

- Hardware: [CERN-OHL-W](https://ohwr.org/cern_ohl_w_v2.pdf)
  - For example, if you release HDL files under CERN-OHL-W and then somebody uses those files in their FPGA, when they distribute the bitstream (either putting it online or shipping a product with it) they do **not** to make the rest of the HDL design available under CERN-OHL-W as well. (based on [source](https://ohwr.org/project/cernohl/wikis/faq#q-what-are-all-these-suffixes))
- Software: [MPL v2.0](https://www.mozilla.org/en-US/MPL/2.0/)
  - The MPL's "file-level" copyleft is designed to encourage contributors to share modifications they make to your code, while still allowing them to combine your code with code under other licenses (open or proprietary) with minimal restrictions. ([source](https://www.mozilla.org/en-US/MPL/2.0/FAQ/))
- Documentation: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
  - This license enables reusers to distribute, remix, adapt, and build upon the material in any medium or format, so long as attribution is given to the creator. The license allows for commercial use. If you remix, adapt, or build upon the material, you must license the modified material under identical terms. ([source](https://creativecommons.org/share-your-work/cclicenses/))

I think this shift allows everyone to use the LumenPnP (and other Opulo source) much more freely, while still ensuring that any improvements make it back to the source.


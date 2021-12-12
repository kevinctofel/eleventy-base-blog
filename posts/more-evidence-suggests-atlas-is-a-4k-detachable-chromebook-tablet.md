---
title: "More evidence suggests Atlas is a 4K detachable Chromebook tablet"
date: "2018-04-11"
categories: 
  - "news"
tags: 
  - "atlas"
  - "chrome-os"
  - "chrome-tablets"
  - "chromebooks"
  - "hp-chromebook-x2"
coverImage: "HP_Chromebook_x2_TabletMode-scaled.jpg"
---

We know that the Chromium OS team is working on a [new Chromebook with the codename of Atlas](https://aboutchromebooks.com/news/chromium-code-suggests-4k-chromebook-code-named-atlas-in-the-works/). And we also know that it will support a 3840 x 2160 display. Now it looks pretty clear that like the [new HP Chromebook x2,](https://aboutchromebooks.com/news/hp-chromebook-x2-arrives-as-the-first-detachable-chromebook-tablet/) shown above, the Atlas will be a Chrome tablet that detaches from a hardware keyboard.

Chrome Unboxed today reported that the [HP detachable was codenamed "Soraka"](https://chromeunboxed.com/detachable-soraka-is-the-hp-chromebook-x2/). The software for Soraka was initially started from an image called "Poppy". It turns out that the software image for Atlas is also built from the files on Poppy. That alone doesn't confirm anything, although it does at least strongly suggest the possibility that the 4K Chromebook will have a detachable display like the HP Chromebook x2.

However, I found another interesting and very relevant [mention of Atlas in the Chromium OS work-in-progress logs](https://chromium-review.googlesource.com/c/chromiumos/overlays/chromiumos-overlay/+/994340) this afternoon:

> atlas: force manual recovery
> 
> this turns on the GBB\_FLAG\_FORCE\_MANUAL\_RECOVERY GBB flag so we don't need a keyboard to get into recovery.

This indicates to me that Atlas will be a tablet-based Chrome OS device with detachable keyboard. If it wasn't, there wouldn't be any need for Chrome OS recovery procedures to work _without_ a keyboard. It appears the tablet would likely use a combination of the power button and volume up/down buttons to navigate through the recovery process, similar to an Android phone.

Keep in mind that while a 4K screen on a Chrome tablet may sound like overkill, [Chrome OS scales the display on high resolution monitors](https://www.androidheadlines.com/2016/11/google-improves-display-scaling-13-inch-chromebooks.html) over a certain size. My Pixelbook screen native resolution is 2400 x 1600, for example but the rendered resolution is essentially a very crisp 1280 x 800. Assuming the same setup for Atlas, you'd really have a full HD or 1920 x 1080 effective resolution that's scaled. That sounds pretty good to me.

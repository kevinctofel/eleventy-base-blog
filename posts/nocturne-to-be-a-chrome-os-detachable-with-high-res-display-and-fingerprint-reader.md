---
title: "\"Nocturne\" to be a Chrome OS detachable with high-res display and fingerprint reader"
date: "2018-04-29"
categories: 
  - "news"
tags: 
  - "chrome-tablets"
  - "chromebooks"
  - "detachables"
  - "hp-chromebook-x2"
  - "nocturne"
coverImage: "HP_Chromebook_x2_FrontRight_Detached-1-scaled.jpg"
---

The [HP Chromebook X2](https://www.aboutchromebooks.com/news/hp-chromebook-x2-arrives-as-the-first-detachable-chromebook-tablet/) shown above will likely be the first Chrome OS detachable to hit the market in June but there's a similar device on the way. A [new Chrome OS board dubbed "Nocturne" appeared this month](https://chromium-review.googlesource.com/c/chromiumos/platform/bmpblk/+/1034152/1/images/boards.yaml), indicating work is underway on the next Chromebook with detachable display.

There aren't yet many Chrome OS code commits for the new board so clearly this project is just getting started. Here's what I've been able to find so far on the details for Nocturne:

- The display will be 2400 x 1600 resolution, same as the current Pixelbook.
- Like the HP Chromebook X2, this device supports code to detect when the [display is removed from a keyboard base](https://chromium-review.googlesource.com/c/chromiumos/platform/ec/+/1032094/2/board/nocturne/base_detect.c). Based on the resolution -- and that this will be a tablet-like device -- I anticipate a sub-13" display.
- Early indications show that the device will support a [fingerprint sensor for biometric authentication](https://chromium-review.googlesource.com/c/chromiumos/overlays/board-overlays/+/1004583/2/overlay-nocturne/profiles/base/make.defaults).
- The board will [run on an Intel Skylake processor](https://chromium-review.googlesource.com/c/chromiumos/platform/depthcharge/+/1025260/5/board/nocturne/defconfig), at least of now. It's possible that in the time it take to design and produce the final product, a newer Kaby Lake processor could be used.

Since it's so early in the product cycle, other details are scarce but I'll be keeping any eye out as Nocturne development continues. I'm not yet sure if Nocturne will be from a third-party hardware partner or is the next iteration in Google's Chromebook hardware cycle. Note too that device specifications and features often change throughout the design process, so consider these details subject to change.

Regardless, it's great to see that we won't be limited to just Chrome OS tablets like the new [Acer Chromebook Tab 10](https://www.aboutchromebooks.com/opinion/why-chrome-tablets-will-be-a-game-changer/), expected to launch in May; aside from Nocturne, we know about [Atlas and its 4K removable display](https://www.aboutchromebooks.com/news/more-evidence-suggests-atlas-is-a-4k-detachable-chromebook-tablet/) as well. These devices are likely geared more towards content consumption instead of creation due to the lack of an integrated keyboard base.

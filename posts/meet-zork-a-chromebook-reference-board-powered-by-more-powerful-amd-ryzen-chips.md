---
title: "Meet Zork: A Chromebook reference board powered by more powerful AMD Ryzen chips"
date: "2019-04-09"
categories: 
  - "news"
tags: 
  - "amd"
  - "chrome-os"
  - "chromebooks"
  - "intel"
  - "ryzen"
  - "zork"
coverImage: "AMD-Chromebook-generic-scaled.png"
---

Nosing through the latest Chromium commits this morning, I found reference to [a new Chrome OS board in the works called Trembyle](https://chromium-review.googlesource.com/c/chromiumos/overlays/chromiumos-overlay/+/1548401). After digging around a little more, it appears that [Zork is the code-name for a reference device using the Trembyle board](https://chromium-review.googlesource.com/c/chromiumos/overlays/board-overlays/+/1525026). Aside from the gaming nostalgia of the name Zork, the more interesting aspect of this device is that it will use an AMD processor that's more capable than the ones used in current Chromebooks.

![](https://i1.wp.com/www.aboutchromebooks.com/wp-content/uploads/2019/04/Zork-picasso-Chromebook.png?fit=800%2C149&ssl=1)

[Zork will be powered by a Picasso chipset](https://chromium-review.googlesource.com/c/chromiumos/overlays/board-overlays/+/1525026), which is similar to the Intel U-Series chips found in high-end Chromebooks today such as the [Acer Chromebook Spin 13](https://www.aboutchromebooks.com/reviews/acer-chromebook-spin-13-review-vs-pixelbook/) and [Lenovo Yoga Chromebook C630](https://www.aboutchromebooks.com/news/lenovo-yoga-chromebook-c630-price-availability-4k/).

Put another way, these aren't the ultra-mobile, lower powered AMD chips you'll see in the [$269 HP Chromebook 14](https://www.aboutchromebooks.com/news/hp-chromebook-14-amd-specs-price-availability-benchmark/), for example. The AMD processor in the HP uses a dual-core, dual-thread CPU with a TDP, or Thermal Design Point, of up to 6W of power, and either a Radeon R4 or R5 GPU, depending on the model.

[Most Picasso chips have four-core CPUs](https://en.wikichip.org/wiki/amd/cores/picasso) and can run more threads simultaneously. They also have TDPs ranging from 15- to 35W, although I'd expect any Chromebooks using these chips to be of the 15W variety, similar to the Intel Core i5 and i7 processors used in the newest mid- to high-end devices.

![](https://i2.wp.com/www.aboutchromebooks.com/wp-content/uploads/2019/04/AMD-Picasson-processors.png?fit=800%2C277&ssl=1)

  

Indeed, if you look at [AMD's 3500U processor above](https://en.wikichip.org/wiki/amd/cores/picasso), it has the same four-core and eight-thread capabilities as the [Intel Core i5-8250U](https://ark.intel.com/products/124967/Intel-Core-i5-8250U-Processor-6M-Cache-up-to-3-40-GHz-) chip found in the above mentioned Acer and Lenovo Chromebooks.

However, the base frequency for AMD's silicon is a faster 2.1GHz compared to the base 1.6GHz of the Core i5. And in turbo or burst mode, the AMD 3500U clocks in at 3.7GHz, slightly above the Core i5's 3.4GHz. All things being equal, the same device using the AMD Picasso _should_ outperform the comparable Core i5.

AMD may also have a relative graphics edge with Picasso although I don't have enough data yet to tell for sure. The only thing I do know is that the Vega 8 GPU has a clock speed of 1.2 GHz while the Intel UHD Graphics 620 ranges from 300MHz to 1.15GHz; both should support full HD and 4K at 60fps although you're not going to run graphically intensive PC games on a Chromebook: [Look to Stadia for that](https://www.aboutchromebooks.com/news/google-stadia-turns-every-chromebook-into-a-pc-gaming-rig/).

As far as the form-factor (or factors?) for Zork, it's difficult to tell although I have seen evidence of a 2-in-1 based on [various motion sensor code mentions and this interesting comment](https://chromium-review.googlesource.com/c/chromiumos/platform/ec/+/1554840/1/baseboard/zork/baseboard.h) regarding the planned reference device folded flat.

![](https://i0.wp.com/www.aboutchromebooks.com/wp-content/uploads/2019/04/Zork-motion-sensors.png?fit=800%2C317&ssl=1)

Since Trembyle and Zork were only committed to Chromium in the past week, it's likely to be at least six, if not more, months before any actual products arrive from this effort. And by then, we could easily see Intel's 9th-generation chips in Chromebooks and Chrome tablets. Even so, it's good to see more Chrome OS choices in terms of hardware such as CPUs and GPUs.

I'll keep an eye out for additional Zork details until we see a product released or until I'm [eaten by a Grue](https://zork.fandom.com/wiki/Grue), whichever comes first.

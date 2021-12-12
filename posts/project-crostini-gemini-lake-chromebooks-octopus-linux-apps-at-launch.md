---
title: "Project Crostini: Gemini Lake Chromebooks likely to have Linux apps at launch"
date: "2018-07-12"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chromebooks"
  - "crostini"
  - "gemini-lake"
  - "intel"
  - "linux"
  - "linux-apps"
  - "octopus"
  - "project-crostini"
coverImage: "Intel-Pentium-Silver-and-Celeron-chip.jpg"
---

Back in December, [Intel announced Gemini Lake](https://newsroom.intel.com/news/introducing-new-intel-pentium-silver-intel-celeron-processors/), a successor chip to Apollo Lake. And there are already Chromebooks in the works for this new chip; some will be [built off a board that's code-named "Octopus", spotted by Chrome Unboxed](https://chromeunboxed.com/first-intel-gemini-lake-chromebook-emerges-octopus/) in February. Interestingly, these devices are likely to be among the first Chromebooks to support [Project Crostini](https://www.aboutchromebooks.com/tag/project-crostini/) -- allowing for Linux app support -- on day one when they launch.

The evidence for this is a new code commit description that [enables a key Project Crostini component for devices built around Octopus](https://chromium-review.googlesource.com/c/chromiumos/overlays/board-overlays/+/1134351):

> octopus: Enable virtual machines Turn VMs on for all Gemini Lake processor based systems.

The actual code is a single line; _two_ lines if you count the leading comment line.

[![kvm-host enable octopus](images/kvm-host-enable-octopus.png)](https://www.aboutchromebooks.com/news/project-crostini-gemini-lake-chromebooks-octopus-linux-apps-at-launch/attachment/kvm-host-enable-octopus/)

If you're not sure what kvm-host is or how it relates to running Android apps on Chrome OS devices, this [excellent write-up from Kieran Miyamoto over at XDA-Developers is a great resource](https://www.xda-developers.com/linux-apps-chrome-os-overview-crostini/). And his unofficial Crostini architecture diagram will give you a quick idea.

[![crostini-architecture](images/crostini-architecture.png)](https://www.aboutchromebooks.com/news/project-crostini-gemini-lake-chromebooks-octopus-linux-apps-at-launch/attachment/crostini-architecture/)

Enabling the KVM host is essential to "linking" the Linux kernel in Chrome OS to Project Crostini containers for Linux app support.

So back to [Intel's new Gemini Lake chips](https://ark.intel.com/products/codename/83915/Gemini-Lake). As of now, there aren't any Chromebooks using it. Instead, the latest devices are either using KabyLake-Y or Apollo Lake processors. The [HP Chromebook X2](https://www.aboutchromebooks.com/news/hp-chromebook-x2-arrives-as-the-first-detachable-chromebook-tablet/) and [Samsung Chromebook Plus v2](https://www.aboutchromebooks.com/news/samsung-chromebook-plus-v2-release-date-price/) use the former chipsets while the Acer Chromebook 11 and Chromebook 15 run on the latter, for example.

Gemini Lake chips will be updated to the Pentium Silver, Celeron J4xxx and the Celeron N4000/N4100 series and here's what [AnandTech, a great technical resource, had to say about the processors when they were announced](https://www.anandtech.com/show/12146/intel-launches-gemini-lake-pentium-silver-and-celeron-socs-new-cpu-media-features):

> The new Gemini Like SoCs feature improved CPU cores over the previous generation, an enhanced media decoding/encoding engine, and a new display pipeline. Intel promises to offer higher performance than predecessors while consuming about 6 W or 10 W, depending on the application. The higher-end Gemini Lake SKUs will be sold under the Pentium Silver brand, whereas the entry-level models will carry the Celeron name.

Essentially, these are updates on the low- to mid-end of Intel's processor range and the chip costs are around $100 to $160. So don't expect to see them in Chromebooks that start at $500 and go up. Instead, these are for the sub-$500 range, which will bring Linux apps to a number of "entry level" Chromebooks, likely later this year.

This is important because I expect Google to make an announcement similar to the one they made in 2017. Back then, it said [Android app support will be available on on all new Chromebooks going forward](https://arstechnica.com/gadgets/2017/01/all-chromebooks-debuting-in-2017-and-beyond-will-run-android-apps/). By building on Project Crostini through 2018 as new processors become available, I'd think Google similarly says that in 2019, all new Chromebooks will support Linux apps out of the box.

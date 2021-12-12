---
title: "Scrolling on Chrome tablets and Chromebooks in tablet mode will move the top UI off screen"
date: "2018-10-01"
categories: 
  - "news"
tags: 
  - "canary-channel"
  - "chrome-os"
  - "chrome-tablets"
  - "chromebooks"
  - "tablets"
coverImage: "HP-Chromebook-x2-hands-on-scaled.jpg"
---

Here's another new feature that Chrome OS is borrowing from Android: [Moving the address bar and other](https://plus.google.com/+FrancoisBeaufort/posts/YzWqcfY4PaP) user interface elements off-screen when scrolling down. The feature is currently in the Chrome OS Canary Channel and might already be available on the Dev Channel as well, although I haven't tested it. Google's François Beaufort shared this image and the news on Monday.

[![](images/chrome-os-tablet-scroll.gif)](https://www.aboutchromebooks.com/chrome-os-tablet-scroll/)

In the demo image, you can see the Chrome navigation bar float off the top of the display when scrolling down; it reappears when scrolling up. This is similar to how browsing in Chrome works on Android phones, allowing you to see more content on the display.

[According to the code change](https://chromium-review.googlesource.com/c/chromium/src/+/1243574/2/chrome/common/chrome_features.cc), this feature will be enabled by default. Some folks may not like that but in fairness to Google: It's a default function of Chrome on Android and I haven't heard anyone complain about it on that platform. ;) Since the code says this "enables or disables" the UI scrolling, there may be a flag setting to disable it.

This a small but useful change that will be appreciated most on smaller tablets and 2-in-1 Chromebooks since the Chrome address bar and controls can take up proportionally more of the display, depending on your screen resolution settings. Even on larger tablets such as the upcoming Pixel Slate -- aka: [Nocturne](https://www.aboutchromebooks.com/tag/nocturne) -- it's a nice touch and one that I plan to use on my Pixelbook: I estimate that I use it in tablet mode at least 50 percent of the time for viewing online content.

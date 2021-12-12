---
title: "Virtual desks for Chromebooks getting a swipe gesture to switch desktops"
date: "2019-07-22"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chrome-os-76"
  - "chrome-os-77"
  - "desktop"
  - "productivity"
  - "stable-channel"
  - "virtual-desks"
coverImage: "Chrome-OS-virtual-desks-workspaces-scaled.png"
---

The Stable Channel of Chrome OS 76 is expected to hit Chromebooks in early August, bringing with it the ability to [use up to four virtual desktops](https://www.aboutchromebooks.com/news/virtual-desks-chrome-os-76-release-chromebooks/). New features such as [keyboard navigation shortcuts](https://www.aboutchromebooks.com/news/chrome-os-76-keyboard-shortcuts-virtual-desks-on-chromebooks/) should be there and there might be one more big one: A four-finger swipe to move between desktops.

If you're not familiar with this feature, it essentially brings to Chrome OS what Linux, macOS, and Windows have had for a long time. Instead of a single desktop or workspace, you can group apps or browsers tabs across multiple "virtual desks", as if you were using multiple physical monitors.

Here's how it looked when I last tested the feature in an early Chrome OS version:

https://youtu.be/6EoXhfruZL4

Missing at that time was a way to quickly switch between the four virtual desks. To do that, I had to swipe up on my trackpad for overview mode to see the desks and then tap on the desk I wanted to use, either via trackpad or touchscreen.

A [new code commit suggests this desk switching will be a little faster and easier](https://bugs.chromium.org/p/chromium/issues/detail?id=866622#c96), similar to how you swipe across a trackpad to switch between browser tabs:

> Add support to handle 4-finger swipe and swipe lift

I can already see some of the work for this code change done on my device with the Dev Channel: Essentially, a three- or four-finger swipe moves between open apps now; eventually, the four-finger gesture will move focus between open virtual desks.

It's a small change but one that brings the virtual desks for Chrome OS even more on par with traditional desktops.

As far as timing goes, it _may_ make the merge cut for Chrome OS 76 but time is running out since the feature freeze date is tomorrow. Obviously, if this function misses the cut, it should appear in Chrome OS 77 at the latest unless Google can sneak it in with a Chrome OS 76 Stable Channel update after the original version is pushed.

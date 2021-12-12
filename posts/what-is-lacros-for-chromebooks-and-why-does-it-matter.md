---
title: "What is LaCrOS for Chromebooks and why does it matter?"
date: "2020-09-14"
categories: 
  - "news"
tags: 
  - "chrome"
  - "chrome-browser"
  - "chrome-os"
  - "lacros"
  - "linux"
coverImage: "Google-Chrome-for-Linux.jpg"
---

Earlier this year, [9to5 Google caught code changes about something called LaCrOS](https://9to5google.com/2020/04/28/google-chrome-os-separate-browser-updates/). Work has progressed on this enough to the point where LaCrOS is available in the Canary Channel of Chrome OS 87, appearing as another Chrome browser icon. That's because Google is decoupling the Chrome browser from Chrome OS on Chromebooks. And it's using Linux to do this.

We know this because of a [Google document explaining what LaCrOS is](https://chromium.googlesource.com/chromium/src.git/+/master/docs/lacros.md) and what it stands for: **L**inux **A**nd **C**h**R**ome **OS**. That's right, the Chrome browser will be independent of Chrome OS and appears to be based on a Linux version of Chrome with improved Wayland support.

![](images/chrome-for-linux-1024x728.jpg)

So why is Google doing this? To be honest, I **_don't_** think it's to [extend the life of older Chromebooks as others covering this news have suggested](https://www.androidpolice.com/2020/09/12/google-is-separating-chrome-from-chrome-os-its-a-big-deal-heres-what-you-need-to-know/).

I'd like to be wrong on that, believe me.

However, that doesn't make much sense since now [all now Chromebooks get approximately 8 years of software update support](https://www.aboutchromebooks.com/news/google-announces-8-years-of-chrome-os-software-updates-aue-for-new-chromebooks/). And it makes even less sense when you think about older Chromebooks currently out of their software support window: How would they get the required update to break out the Chrome browser from Chrome OS?

Instead, I think this is mainly to help Google better manage work on the Chrome browser and get browser updates faster to Chromebooks by making the platform more modular.

Have you ever wondered why Chrome OS updates are typically delivered a week or two after Chrome updates for all other platforms? That's partially because Chromebooks aren't just getting browser updates; they're getting software platform updates for Chrome OS as well.

By decoupling the Chrome browser from Chrome OS, Google can manage a single Chrome code base for all platforms and push browser updates out to those platforms at the same time. And on the flipside, Chrome OS updates that might be ready for deployment don't have to be held up by Chrome browser updates.

The LaCrOS document suggests that there might be a slight performance hit with a separate Chrome browser. That's because Chrome OS will use APIs to communicate with the browser instead of native code for such communication:

> The basic approach is to rename the existing binary to ash-chrome, with minimal changes. We then take the linux-chrome binary, improve its Wayland support, make it act like the web browser on Chrome OS, and ship that as the lacros-chrome binary. This allows the two binaries to be released independently, with some performance/resource costs. The API boundary initially will be semi-stable: it will tolerate 1-2 milestones of version skew. We may allow larger amounts of skew in the future.

I don't expect that performance hit to be very noticeable however. And as noted, you may see your Chromebook running on Chrome OS 90, for example, while your browser version is 91. That won't likely matter to the end user experience either, although you may have some new browser features before you get a Chrome OS update, which is a good thing.

I'm sure people have thoughts and opinions on this approach by Google, so let's hear them in the comments!

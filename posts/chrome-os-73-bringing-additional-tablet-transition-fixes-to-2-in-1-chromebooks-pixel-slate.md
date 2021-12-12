---
title: "Chrome OS 73 bringing additional tablet transition fixes to 2-in-1 Chromebooks, Pixel Slate"
date: "2019-03-17"
categories: 
  - "news"
tags: 
  - "2-in-1s"
  - "chrome-os"
  - "chrome-os-73"
  - "chromebooks"
  - "pixel-slate"
coverImage: "Pixel-Slate-in-hand-e1548958329495-scaled.jpg"
---

Perhaps the initial biggest issue with the [Google Pixel Slate](https://www.aboutchromebooks.com/reviews/google-pixel-slate-review/) was the terrible animation performance when switching apps in tablet mode. I'd say that the second biggest was [offering the Slate with an](https://www.aboutchromebooks.com/news/celeron-pixel-slate-review-video/) [under-powered](https://www.aboutchromebooks.com/news/celeron-pixel-slate-review-video/) [processor for the base model](https://www.aboutchromebooks.com/news/celeron-pixel-slate-review-video/), but that's a different issue else entirely.

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" align="right" src="//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&amp;OneJS=1&amp;Operation=GetAdHtml&amp;MarketPlace=US&amp;source=ac&amp;ref=qf_sp_asin_til&amp;ad_type=product_link&amp;tracking_id=aboutchromebo-20&amp;marketplace=amazon&amp;region=US&amp;placement=B07JWCHWRM&amp;asins=B07JWCHWRM&amp;linkId=023e2446228afbe24a1e2ea14ffc64ef&amp;show_border=true&amp;link_opens_in_new_window=true&amp;price_color=333333&amp;title_color=0066c0&amp;bg_color=ffffff"></iframe>

Google did plan to address the [tablet app animation issues with some fixes](https://www.aboutchromebooks.com/news/pixel-slate-tablet-animation-lag-fix/), but its work isn't done yet: [According to a related bug report](https://bugs.chromium.org/p/chromium/issues/detail?id=932887), more optimizations are coming in Chrome OS 73... and beyond.

The [open bug is actually for a lower-end Chromebook based on the Coral board](https://crbug.com/932887), of which there are more than a half dozen. However, it relates to choppy transitions and dropped framerates in overview mode for app switching. One workaround that helped was to disable a Chrome OS flag that causes the background to blur in overmode, but that's not a long term solution.

This recent comment from the Chromium developer team suggests that not all of the visual transition fixes made their way into Chrome OS 72:

> There are optimization for normal (w/o maximize window) scenario that couldn't make into 72. They'll be in 73 and we keep working on performance turning, so stay turned.

According to the Chromium release calendar, [Chrome OS 73 should hit the Stable Channel this Tuesday, March 19](https://chromiumdash.appspot.com/schedule), following last week's push of the [same version to enterprises, which enabled Linux app support](https://www.aboutchromebooks.com/news/chrome-os-73-brings-linux-app-support-managed-guest-sessions-to-enterprises/). So any of the newer optimizations should be seen soon for testing.

Even better -- to me, anyway -- is that the team is continuing to gather telemetry metrics and logs to continue improving overview mode and app switching when devices are used as tablets.

When I use my Pixel Slate, I actually never use overview mode so the animations are a non-issue for me personally. Yes, this is a real issue and it's really inexcusable, but I never see it: I don't run numerous apps at the same time and even when I'm multitasking, that's typically because I'm creating content and have the Pixel Slate Keyboard attached, pressing Alt+Tab to quickly move around between apps.

I also suspect that the more you spend on a Pixel Slate, the less of an impact there is. Meaning, the higher-powered processors combined with more memory manage the app transitions far better than the base model. Here's [a look at the transitions on both the Core m3 and Core i5](https://www.aboutchromebooks.com/news/pixel-slate-core-m3-vs-i5-performance-video/) Pixel Slate, which perform noticably better than the Celeron edition.

https://youtu.be/GzZGx8DpBu4

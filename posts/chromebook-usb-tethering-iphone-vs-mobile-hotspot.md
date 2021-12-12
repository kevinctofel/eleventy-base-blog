---
title: "Chromebooks may soon support USB tethering to iPhones for internet access"
date: "2019-07-08"
categories: 
  - "news"
tags: 
  - "bluetooth"
  - "chrome-os"
  - "hotspot"
  - "instant-tethering"
  - "ios"
  - "iphone"
  - "linux"
  - "usb"
  - "usb-c"
  - "wi-fi"
coverImage: "iPhone-and-Chromebook-e1582644467408-scaled.jpg"
---

It only took six years, but Google is finally making progress on supporting iPhones to provide web access to Chromebooks over USB. [A bug was opened for this feature back in 2013](https://bugs.chromium.org/p/chromium/issues/detail?id=221309) and [Chrome Unboxed spotted a code commit to eventually add this feature](https://chromeunboxed.com/chrome-os-is-adding-support-for-usb-tethering-to-iphones/).

Sure, you can use an iPhone as a wireless mobile hotspot for a Chromebook today. So why is this a big deal?

The answer is in the description of the code commit:

> iPhone tethering through USB consumes less battery than wireless or Bluetooth tethering and is much safer. Based on user reports, it is also more reliable than Wifi tethering.

Essentially, you don't need your Chromebook's Wi-Fi or Bluetooth radios on if you're using a USB cable and a phone for your internet connection.

That means your Chromebook will run longer on a charge when tethered as compared to a wireless hotspot. Some of that battery savings might be offset by the fact that a Chromebook can charge a mobile device that's connected over USB, so keep that in mind.

You'd think that the audience for this feature is small as it just "makes sense" to use an Android phone with a Chromebook, particularly since [Chrome OS supports Instant Tethering](https://www.aboutchromebooks.com/news/google-expands-instant-tethering-connection-to-15-chromebooks-and-30-android-phone-models/).

But there are many enterprises and small businesses that have fleets of iPhones deployed, even if the employees are using Chromebooks. And frankly, as I've noted before, [you can be a very happy Chromebook user with an iPhone](https://www.aboutchromebooks.com/opinion/can-you-happily-use-a-chromebook-and-an-iphone-yup/). That's largely due to great support on iOS for the many of the same Google apps and services natively found in Chrome OS.

This feature requires an actual Linux kernel change underneath Chrome OS, so it's not a simple or quick change. As a result, there's no documented target for when Google will add USB tethering for iPhones on a Chromebook. Additionally, as we saw with the long rollout of [Project Crostini](https://www.aboutchromebooks.com/tag/project-crostini), some older Chromebooks _never_ got the feature, which required a specific version of Linux.

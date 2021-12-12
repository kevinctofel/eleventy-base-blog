---
title: "Chromebooks getting support for USB Wi-Fi dongles"
date: "2018-07-25"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chromebooks"
  - "usb"
  - "wi-fi"
coverImage: "wifi-usb-scaled.jpg"
---

Apparently, the Chromium team has seen reports of "wonky" Wi-Fi connections on Chromebooks and other Chrome OS devices. I've never had issues using the internal Wi-Fi radio on my Chromebooks, but of course, that's a minutely small sample. As a result, the team will be [adding support for certain USB Wi-Fi dongles](https://chromium-review.googlesource.com/c/chromiumos/third_party/kernel/+/1149450) so users will have backup connectivity if the internal wireless radios aren't up to snuff in some environments.

Here's the change log description of this work in progress:

> "USB Wifi can sometimes be helpful as a backup, if the internal Wifi is wonky. There are various popular USB Wifi dongles on the market that use varieties of this Ralink chipset. Let's enable support for some newer ones."

If you have an older Wi-Fi dongle -- say one that works with 802.11b or g networks, this change won't likely help you. But 802.11n and ac dongles using Ralink's 33xx, 35xx and 53xx chipsets are planned for support.

Note that MediaTek bought Ralink in 2011 and although the company's Wi-Fi dongles may be branded by either name, they often power dongles with other, often more recognizable brand names. Hopefully, some of the USB Wi-Fi devices support USB-C without an adapter since many newer Chromebooks have moved on to that format.

---
title: "After 7 years, a bug fix will let Chromebooks use a USB-connected iPhone for mobile broadband"
date: "2020-02-25"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chromebooks"
  - "iphone"
  - "linux"
  - "mobile-broadband"
  - "usb"
coverImage: "iPhone-and-Chromebook-e1582644467408-scaled.jpg"
---

It's not often I see a Chromium bug that's seven years old, but today I revisited one because of some major progress made. And when I say seven years, I mean **_to the day_**: This [feature request to use an iPhone's mobile broadband connection over USB on a Chromebook Pixel](https://bugs.chromium.org/p/chromium/issues/detail?id=221309) was submitted on February 25, 2013!

I noted back in June of last year that you [couldn't USB tether an iPhone to a Chromebook for connectivity](https://www.aboutchromebooks.com/news/chromebook-usb-tethering-iphone-vs-mobile-hotspot/) but that the Chromium team was looking into it.

I was never too concerned about not having this feature because the few times I've needed a Wi-Fi hotspot for my Chromebooks, I've just shared the iPhone's connection over Wi-Fi.

While the Personal Hotspot feature of iOS does work, there's a case to be made for sharing that connection over USB, and it's right in the feature request:

> Phone tethering through USB consumes less battery than wireless or Bluetooth tethering and is much safer. Based on user reports, it is also more reliable than Wifi tethering.

Yup, I'd agree. And thankfully, after many years, [code to address this was updated to support this feature earlier this month](https://chromium-review.googlesource.com/c/chromiumos/third_party/kernel/+/2006388). There's no release date assigned to this code change as of yet, so I'm not sure when it will appear.

Why was there little to no movement on this feature since last July? It wasn't a simple code fix; instead, all of the supported Linux kernels for Chrome OS needed updates before the feature could be rolled out.

I'm generally a [very happy user of both iPhone and Chromebook](https://www.aboutchromebooks.com/opinion/can-you-happily-use-a-chromebook-and-an-iphone-yup/) on a daily basis, even without USB tethering support. But that's just me: Will you be using a USB connected iPhone with your Chromebook?

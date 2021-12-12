---
title: "These are the Chromebooks that won't be getting Linux apps through Project Crostini"
date: "2018-08-22"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chromebases"
  - "chromebooks"
  - "chromeboxes"
  - "crostini"
  - "linux"
  - "linux-apps"
  - "project-crostini"
coverImage: "chromebook-pixel-2015-side-closing-press-scaled.jpg"
---

I hate to share this news, but I've always felt bad news doesn't get better with age. Sadly, [a new code commit from Tuesday confirms that any Chrome OS devices running on the Linux kernel version 3.14](https://chromium-review.googlesource.com/c/chromiumos/docs/+/1181782) (or older) will _**not**_ be getting [Project Crostini](https://www.aboutchromebooks.com/tag/project-crostini) support.

[This commit was found by Redditor keeto](https://www.reddit.com/r/Crostini/comments/99gpkw/chromebooks_with_314_kernel_will_not_get_linux/) and I scoured through the code to double-check the information. Unfortunately, it's legit:

> containers\_and\_vms: drop support for linux-3.14 and older
> 
> Since vsock (and other security patchsets) aren't being backported to linux-3.14, update the docs to match.

So to save everyone some trouble, I hit up the [Developer Information Page for Chrome OS Devices](https://www.chromium.org/chromium-os/developer-information-for-chrome-os-devices) to create the following list of devices that will not be able to run Linux apps in a container due to their kernel version.

- Acer Chromebase
- HP Chromebook 14 G3
- Acer Chromebook 13 (CB5-311)
- Acer C670 Chromebook 11
- ASUS Chromebook Flip C100PA
- ASUS Chromebook C201
- Acer Chromebox CXI2
- Acer Chromebase 24
- Toshiba Chromebook 2 (2015 Edition)
- Lenovo ThinkCentre Chromebox
- Google Chromebook Pixel (2013)\*
- Google Chromebook Pixel (2015)\*
- Acer Chromebook 15 (2015)
- Dell Chromebook 13 7310\*
- ASUS Chromebox CN62
- AOpen Chromebase Mini
- Asus Chromebit CS10
- AOpen Chromebox Mini

While this is bad news for any owners of these devices, the one that really stands out to me is the Google Chromebook Pixel from 2015. Why? Because the original 2013 Chromebook Pixel has a higher kernel version. That really makes _**no**_ sense to me. _**(Note: See update below)**_

[![Project Crostini Terminal](images/Project-Crostini-Terminal.png)](https://www.aboutchromebooks.com/news/dev-channel-update-68-0-3437-0-fixes-terminal-app-for-project-crostini/attachment/project-crostini-terminal/)

As we knew prior, only devices with [Linux kernel 3.18 and above were targeted for Crostini](https://www.aboutchromebooks.com/news/theres-hope-that-older-chromebooks-will-run-linux-apps-with-crostini/). And the bulk of Chrome OS devices still supported have or will have Project Crostini for full Linux app support. Even so, this doesn't lessen the blow to those device owners that were hoping to get the feature.

So again, sorry for the bad news. Don't shoot the messenger!

\*_**Update**_: [Based on this information](https://www.aboutchromebooks.com/news/2015-chromebook-pixel-may-get-project-crostini-linux-apps/), it's still yet possible that the 2015 Chromebook Pixel and the Dell Chromebook 13 7310 may get Crostini support. However, the 2013 Chromebook Pixel definitely is not: It has the kernel version but the Intel Ivy Bridge chip negates the possibility.

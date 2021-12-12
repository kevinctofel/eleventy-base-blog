---
title: "Chrome OS to bring Android VPN support for Linux apps on Chromebooks"
date: "2019-03-23"
categories: 
  - "news"
tags: 
  - "android"
  - "chrome-os"
  - "chrome-os-74"
  - "chrome-os-75"
  - "crostini"
  - "linux"
  - "project-crostini"
  - "security"
  - "vpn"
coverImage: "Chrome-OS-VPN-settings-scaled.png"
---

Back in February, I noted that the Chromium team was working to [add VPN support in Linux containers running on Chromebooks](https://www.aboutchromebooks.com/news/vpn-tun-support-linux-on-chromebooks-project-crostini/). Now there appears to be a second VPN option in the works: As spotted by 9to5 Google, [there's an effort to extend any Android-based VPN apps to Linux](https://9to5google.com/2019/03/22/linux-apps-chrome-os-android-vpn/).

Currently, you can use a VPN Android app on a Chromebook and the security will work within Chrome OS, so you can privately browse the web. However, such a setup doesn't support any browsing or app usage in a Crostini container running Linux.

The [brief summary description of the code change](https://chromium-review.googlesource.com/c/chromiumos/platform2/+/1536031) in progress only says:

> This CL adds Crostini VM interfaces to the whitelisted networking interfaces that route traffic through VPNs.

If you look at the [associated bug for the code change](https://bugs.chromium.org/p/chromium/issues/detail?id=834585), however, you'll get a clearer picture of the problem the developer team is trying to solve.

As a test, an Android VPN app was installed on a Chromebook and then enabled. Next, a Linux container was created and used to surf to a website that can show you your IP address. If the Android VPN carried over to the Linux container then, the user's IP address wouldn't appear. Instead, the IP address of the VPN proxy server would. Alas, that did not happen, exposing the lack of VPN support from Android in Chrome OS to Linux.

The bug report isn't yet associated with a Chrome OS release version and at this point, the earliest we might see this feature availability is Chrome OS 74. However, [that version hit its Beta Promotion stage last week](https://chromiumdash.appspot.com/schedule), so I'm thinking Chrome OS 75 will be the target. You can always "star" the bug for updates though and at some point, it will show the targeted release date.

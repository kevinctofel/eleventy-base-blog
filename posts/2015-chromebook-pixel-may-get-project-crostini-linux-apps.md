---
title: "Hold the phone: There's hope that the 2015 Chromebook Pixel will get Project Crostini after all"
date: "2018-08-23"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chromebook-pixel"
  - "chromebooks"
  - "crostini"
  - "dell-chromebook-13"
  - "linux"
  - "linux-apps"
  - "project-crostini"
coverImage: "Chromebook-Pixel-scaled.jpg"
---

Yesterday, I shared the bad news that around [a half-dozen Chrome OS devices would not gain support for Linux apps in Project Crostini](https://www.aboutchromebooks.com/news/these-are-the-chromebooks-that-wont-be-getting-linux-apps-through-project-crostini/). The most surprising member of that list is the 2015 Chromebook Pixel. Now, it appears that perhaps that Chromebook as well as the Dell Chromebook 13 7310, could still see Linux app support.

[Android Police](https://www.androidpolice.com/2018/08/22/google-confirms-many-older-chromebooks-wont-get-linux-apps-including-2015-chromebook-pixel/) found a [Google Groups thread that explains the situation](https://groups.google.com/a/chromium.org/forum/#!msg/chromium-os-dev/D_GJtOzmTC4/UXR5Ik9UCQAJ). Here's the most relevant comment:

> \[W\]e've only decided that we're not going to support linux-3.14 and older. we've also only decided that we're not going to support specific devices that have been listed in the doc. there remains an undecided gap in between into which lulu & samus fall.

For reference, Samus is the internal name for the 2015 Chromebook Pixel, while Lulu is the Dell Chromebook 13. As far as the document that's pointed out, you can [view it here](https://chromium.googlesource.com/chromiumos/docs/+/master/containers_and_vms.md#Supported-Now). By they way, I've had the doc bookmarked for months because it's a great overview of the nuts and bolts of how containers work in [Project Crostini](https://www.aboutchromebooks.com/tag/project-crostini).

Essentially, there's no decision yet on these two devices, so it's still possible that they do see support for Linux apps. If I had to guess -- and I said this in a comment earlier today in the original post -- my gut says that at least the 2015 Chromebook Pixel will get it. But that's just a guess. My thought is that there are quite a few owners of that Chromebook and if enough of them speak up in support of adding Crostini, Google could make it happen.

On a related note, I mentioned yesterday that the 2013 Chromebook Pixel is already on a supported kernel for this project so I didn't include it on the "won't be supported list." However, that device -- known as Link -- runs on an older Ivy Bridge Intel processor so Crostini isn't coming to that Chromebook. I'll update the list as a result.

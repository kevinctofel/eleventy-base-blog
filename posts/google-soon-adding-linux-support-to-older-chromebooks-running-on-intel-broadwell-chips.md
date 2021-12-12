---
title: "Google soon adding Linux support to older Chromebooks running on Intel Broadwell chips"
date: "2020-01-06"
categories: 
  - "news"
tags: 
  - "acer"
  - "asus"
  - "chromebases"
  - "chromebook-pixel-2015"
  - "chromeboxes"
  - "crostini"
  - "google"
  - "lenovo"
  - "linux"
  - "linux-apps"
  - "project-crostini"
  - "toshiba"
coverImage: "Viewing-the-Downloads-folder-in-Linux-on-a-Chromebook-scaled.png"
---

Not all of the [latest Chromebook news is happening at CES 2020](https://www.aboutchromebooks.com/tag/ces-2020/), although the latest Chromebooks are appearing there. In fact, there's some great news for Chromebooks that first launched in 2015: All nine Chrome OS devices running on the Intel Broadwell chipset are getting the ability to run Linux via Project Crostini.

A [code commit from just a few days ago](https://chromium-review.googlesource.com/c/chromiumos/overlays/board-overlays/+/1986938) tipped the news with this description:

> enable crostini on all BDW boards
> 
> samus already has crostini unconditionally enabled via this commit: commit 9da9edee2d44 ("Always use v4.14 kernel and audio config for samus")
> 
> Enable it in the rest of the BDW systems.

The "BDW" in this case stands for Broadwell and these are the nine devices powered by that chipset:

- Acer C670 Chromebook 11
- Acer Chromebook CXI2
- Acer Chromebase 24
- Toshiba Chromebook 2 (2015 edition)
- Lenovo ThinkCentre Chromebox
- Google Chromebook Pixel 2015
- Acer Chromebook 15
- Dell Chromebook 13 7310
- Asus Chromebox CN62

The standout device here, at least to me, is the Google Chromebook Pixel 2015 as many folks still own and run that 2-in-1. In fact, that was the first of the Broadwell-based Chrome OS devices to [get experimental Crostini support back on Chrome OS 77](https://www.aboutchromebooks.com/news/chrome-os-77-to-bring-crostini-linux-beta-to-chromebook-pixel-2015-other-older-devices/) as part of the "kernelnext" software effort. The eight other devices should be following suit soon.

![](images/Chromebook-Pixel-1024x577.jpg)

Since the code commit just landed and the bug is listed as private, I can't tell which Chrome OS release will include the change to add Crostini support to the above devices.

I did double-check the release log for Chrome OS 80 Dev Channel and didn't find it there, however that release dropped back in December. With the code change being more recent, it makes sense that I didn't find it.

I'll keep an eye out for this in the next Dev Channel although it could already be present in the Canary Channel for Chrome OS. I'm at CES using the Pixelbook Go for coverage so I'm not about to throw Canary on my only current production machine. ;)

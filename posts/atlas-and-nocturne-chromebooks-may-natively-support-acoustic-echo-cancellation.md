---
title: "Atlas and Nocturne Chromebooks may natively support Acoustic Echo Cancellation"
date: "2018-09-14"
categories: 
  - "news"
tags: 
  - "atlas"
  - "audio"
  - "chrome-os"
  - "chromebooks"
  - "hangouts"
  - "nocturne"
  - "pixelbook-2"
coverImage: "hangouts-chrome-os.jpg"
---

Chromebooks are great for video chats using Hangouts and they may be getting even better. Well, at least two of them, that is. While researching some audio internals for the still-in-progress Atlas and Nocturne Chromebooks, I came across [this interesting comment about them from June](https://groups.google.com/a/chromium.org/d/msg/chromium-os-reviews/825LYZzzfh0/2BO_OA8qBQAJ).

> For Nocturne & Atlas, we are trying different new features like AEC capture & Waves etc. For this, we are anticipating changes in m/c driver. We are in the middle of enabling those new features for these platforms. We believe by end of this month or a week earlier, we will finish enabling those features. As soon as it is done, we will work on upstream and their review comments. So, meanwhile we want to have CPFE enabled with Audio. Thank you.

 

My interpretation of AEC may be incorrect, but I believe in this context it stands for Acoustic Echo Cancellation. This would reduce the chance of your own voice being picked up on the other end of a voice or video call and is based in part on the DSP, or Digital Signal Processor being used.

In the case of Atlas and Nocturne, this is likely an Intel DSP solution, given that both are expected to run on fairly current Intel processors. Additionally, some of my findings on AEC support are from the change [adding the Kaby Lake Max98373 driver for audio on both boards](https://chromium-review.googlesource.com/c/chromiumos/third_party/kernel/+/1033465).

While this isn't a huge development, it is a welcome one. To me it is, anyway: Most of my video and voice conversations are done on a Chromebook today and it drives me batty when I hear my words echoed back to me. Then again, some of my words probably drive the other party batty the **_first_** time. ;)

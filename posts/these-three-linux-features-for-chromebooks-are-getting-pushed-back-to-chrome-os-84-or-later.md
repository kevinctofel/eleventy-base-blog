---
title: "These three Linux features for Chromebooks are getting pushed back to Chrome OS 84 or later"
date: "2020-04-17"
categories: 
  - "news"
tags: 
  - "arduino"
  - "backup"
  - "chrome-os"
  - "chrome-os-84"
  - "chrome-os-85"
  - "chromebooks"
  - "crostini"
  - "developers"
  - "disk-resizing"
  - "linux"
  - "project-crostini"
  - "usb"
coverImage: "Restore-Linux-Crostini-apps-and-files-1-scaled.jpg"
---

I've been tracking several Chrome OS Linux -- aka: [Crostini](https://www.aboutchromebooks.com/tag/crostini/) -- bugs and feature requests that were expected to arrive in Chrome OS 81 but didn't make it.

Most of the reason for the situation is related to Google choosing to skip Chrome OS 82 due to changing work schedules in light of the Covid-19 pandemic. But some of the features won't be in Chrome OS 83 either as a result of bug prioritization.

Here's what's getting punted to Chrome OS 84, or even 85:

## Allow restores from a backup in the Crostini setup flow

![](images/Restore-Linux-Crostini-apps-and-files-1024x715.png)

To be fair, this feature is more of a time-saver than any new functionality. In other words, you can currently [restore a Crostini backup on a Chromebook, ever since Chrome OS 74](https://www.aboutchromebooks.com/news/chrome-os-74-dev-channel-how-to-backup-restore-linux-container-crostini/). But what you can't do is _skip_ the empty Linux container setup before you restore your backup.

And that's what this feature request, currently in the form of a Chrome OS bug, will bring: A little time savings and no need to download the Crostini container during the setup process.

I think the latter advantage is the larger one here since you can't currently create a Linux container on a Chromebook without a network connection. By restoring a Crostini backup that might be on external media, you could get going on Linux in a matter of minutes, even without that network connection. As of now, [this feature has been moved to Chrome OS 85](https://bugs.chromium.org/p/chromium/issues/detail?id=944200#c19).

## Crostini / Linux Disk Resize after setup

![](images/Linux-username-and-storage-on-Chromebook-1024x683-1.jpg)

With [Chrome OS 81 recently released](https://www.aboutchromebooks.com/news/chrome-os-81-stable-channel-release-what-you-need-to-know/), you can use an experimental Chrome flag ([chrome://flags#crostini-disk-resizing](//flags#crostini-disk-resizing)) to customize the amount of space your Linux container will use.

But that's not the full functionality of what's expected because disk resizing is also useful _after_ the fact, meaning when you're running low on local storage space. And that's not something you can do now.

I anticipate the option will appear in the Linux Settings menu on Chrome OS so that as your Linux partition needs room to grow, you can move a slider and let the operating system rejigger your storage. Regardless of how disk resizing "in-flight" will work, [it's not coming until Chrome OS 84 as of now](https://bugs.chromium.org/p/chromium/issues/detail?id=858815#c76).

## Crostini serial device USB support

Most Chromebook users won't care about this feature request since it's mostly for people (like me!) who want to [develop on USB-connected microcontrollers such as Arduino boards](https://www.aboutchromebooks.com/news/how-to-code-an-arduino-with-a-chromebook/).

https://youtu.be/FuO8ANfFKFw

Then again, there's a case to be made for folks who want to use Chrome OS with a USB input device such as a drawing tablet, a currently unsupported USB peripheral, or some other serial input product.

And to be fair, it appears that most of the work is done for this. In fact, with [Chrome OS 77 we gained experimental features that allow for Linux connections to unsupported USB devices](https://www.aboutchromebooks.com/news/chrome-os-77-stable-channel-arrives-heres-what-you-need-to-know/). However, not every unsupported USB device is currently recognized due to security reasons.

The Chrome OS team has been whitelisting specific devices for months which is why some work and some don't. There may be a blanket security approval for all devices in the future or a "permissions broker", but the details haven't yet been shared, nor coded.

[Indeed, the developer who owns the bug this week](https://bugs.chromium.org/p/chromium/issues/detail?id=956288#c62) commented:

> Unfortunately, we're a small team and can't work on all features we want simultaneously. This is one of the features that has had to take a back seat for now. I'm hoping to get some cycles for this soon, but until then, please bear with us.

This comment was in response to a reaction when the feature was recently pushed out to Chrome OS 84, expected to hit the Stable Channel on or around July 21, 2020.

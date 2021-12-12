---
title: "Updated Chrome OS 91 Stable Channel fixes broken clipboard in Linux on Chromebooks"
date: "2021-07-02"
categories: 
  - "news"
tags: 
  - "bugs"
  - "chrome-os"
  - "chrome-os-91"
  - "chromebooks"
  - "linux"
  - "linux-apps"
  - "linux-on-chromebooks"
coverImage: "Acer-Chromebook-Spin-513-running-Linux-apps-e1613743396149.jpg"
---

I often tell readers to submit a bug report when they spot some issue in Chrome OS. Some do, but others tell me "Google doesn't listen to our feedback." To be honest, it's downright impossible to listen to feedback that's never shared! That's why I'm happy to see people who couldn't copy and paste between Chrome OS and Linux actually **_did_** report the issue to Google. A [Chrome OS 91 Stable Channel update was released this week](https://chromereleases.googleblog.com/2021/06/stable-channel-update-for-chrome-os_30.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GoogleChromeReleases+%28Google+Chrome+Releases%29) and it fixes the broken clipboard in Linux on Chromebooks.

Google didn't specifically mention this issue was resolved in its blog post, which is why I'm calling attention to it.

I, along with another 20 or so folks, starred the bug so I was notified of the fix. [Google did provide a link to the fixes in Chrome OS 91](https://bugs.chromium.org/p/chromium/issues/list?sort=&groupby=&colspec=ID%20Pri%20M%20Stars%20ReleaseBlock%20Cr%20Status%20Owner%20Summary%20OS%20Modified&x=m&y=releaseblock&cells=tiles&q=os%3Dchrome%20M%3D91%20status%3DFixed&can=1) though, so anyone could have clicked through to find this.

[Here are the specifics](https://bugs.chromium.org/p/chromium/issues/detail?id=1205764&sort=-modified&groupby=&colspec=ID%20Pri%20M%20Stars%20ReleaseBlock%20Cr%20Status%20Owner%20Summary%20OS%20Modified&x=m&y=releaseblock&cells=tiles&q=os%3Dchrome%20M%3D91%20status%3DFixed&can=1) if you'd rather just see the history of this particular issue. And here's a report of the problem to illustrate the clipboard behavior.

_"Steps to reproduce: take a full-window screenshot from a 1440p monitor, cannot paste into LibreOffice Writer; in addition, my main concern was not being able to copy anywhere about 150 lines of content into VS code from the browser."_

![LibreOffice in Linux on Chromebooks](images/LibreOffice-on-Chromebook.jpg)

[LibreOffice on a Chromebook is easy to install](https://www.aboutchromebooks.com/news/how-to-install-libreoffice-for-linux-on-a-chromebook-after-downloading-it-as-a-tar-gz-file/)

Interesting, at least to me, is that the Chromebook clipboard was saving data if the amount of that data was relatively small.

A few hundred bytes, say a couple of sentences, could be copied from Linux and pasted into Chrome OS, or vice versa. Too much data though and the issue became apparent. So a larger amount of text or just about any image would disappear into the ether, never to be seen again.

It's likely your Chromebook has already notified you that a Chrome OS 91 software update is available or has been downloaded. If so, you'll have Chrome OS 91 (91.0.4472.147), along with a working clipboard for Linux on Chromebooks, after a quick restart.

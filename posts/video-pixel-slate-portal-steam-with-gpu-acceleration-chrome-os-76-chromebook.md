---
title: "Video: Pixel Slate gaming demo in Steam, with GPU and without on Chrome OS 76"
date: "2019-05-23"
categories: 
  - "how-to"
  - "news"
tags: 
  - "chrome-os"
  - "crostini"
  - "dev-channel"
  - "flags"
  - "gaming"
  - "google-pixel-slate"
  - "gpu"
  - "pixel-slate"
  - "project-crostini"
  - "settings"
coverImage: "Portal-on-the-Pixel-Slate-scaled.png"
---

I mentioned earlier this month that [a new flag in Chrome OS 76 would make it easier to enable GPU acceleration for Linux on a Chromebook](https://www.aboutchromebooks.com/news/chrome-os-76-will-make-it-easier-to-enable-gpu-acceleration-on-chromebooks/). That's great because I've never gotten it to work with the command line method.

My Dev Channel Pixel Slate [was updated to Chrome OS 76 earlier today](https://chromereleases.googleblog.com/2019/05/dev-channel-update-for-chrome-os.html) so I tested the flag and it works. I'm not sure if it will enable GPU acceleration to every Chromebook that supports Linux, but I know the Pixel Slate specifically has this function, as do [several Chromebooks](https://www.aboutchromebooks.com/news/pixelbook-and-nami-chromebooks-the-first-to-get-linux-gpu-acceleration-in-project-crostini/) and [Chromeboxes](https://www.aboutchromebooks.com/news/four-chromeboxes-next-up-to-get-gpu-acceleration-for-linux-likely-in-chrome-os-74/).

So what do you get when you enable GPU acceleration? I did a quick video of the game Portal on Steam before and after turning on the GPU. The difference is _very_ obvious: Without the GPU doing some work, even an old game like this is unplayable.

https://youtu.be/0uEjo-jzPHg

After enabling GPU acceleration it's far better; not what I'd call fantastic but what do you expect with an integrated GPU running a game inside of [a Linux container which is inside a virtual machine](https://www.aboutchromebooks.com/news/video-how-project-crostini-works-run-linux-apps-on-chromebooks/)? ;)

I'm glad to see the GPU functionality but I likely won't use it for gaming. My hope is that I'll see some improved performance with app design and layout in Android Studio. Ideally, it would be nice to see a virtual device emulator there for app testing as well.

[Project Stadia is where I'm pinning my gaming hope on a Chromebook](https://www.aboutchromebooks.com/news/google-stadia-turns-every-chromebook-into-a-pc-gaming-rig/): It will matter far less if your Chromebook has a good GPU while your connection speed will be far more important.

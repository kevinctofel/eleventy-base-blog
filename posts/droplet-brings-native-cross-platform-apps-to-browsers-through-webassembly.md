---
title: "Droplet brings native cross-platform apps to browsers through WebAssembly"
date: "2018-04-05"
categories: 
  - "news"
tags: 
  - "chrome"
  - "chrome-os"
coverImage: "Screenshot-2018-04-05-at-12.34.47-PM-scaled.png"
---

Hats off to ChromeUnboxed, which has been [following the efforts of Droplets for several months](https://chromeunboxed.com/windows-apps-on-your-chromebook-without-emulators-or-vm-meet-droplet/). Today, [Droplet Computing unveiled its newest product](https://dropletcomputing.com/droplet-computing-unveils-at-cloud-field-day/), which combines manageable containers and [WebAssembly](http://webassembly.org/) technology to run native desktop apps directly in Chrome and on Chrome OS devices such as Chromebooks. Yes, if you want to run the full version of Microsoft Office on a Chromebook, even when you're offline, for example, this technology makes it possible.

Keep in mind a few things. First, WebAssembly works on all of the major browsers, so this isn't a Chromebook-only thing. You can use the technology on Edge, Firefox and Safari too, meaning Windows apps on a Mac as one possibility.

Second, while upon first glance it may seem like [Droplet](https://dropletcomputing.com/) is installing Virtual Machines or emulators on different computing devices, but that's not what this. Essentially, developers can compile their C, C++ or Rust code into WebAssembly so that their apps run in a browser window with very little performance degradation.

I won't go into all of the technical details since all I have to go on is Droplet's first public presentation from this morning. There were some basic examples and demos and a ton of technical information that I'm still trying to digest. I did capture some screenshots of the presentation that shows you an overview of what the company is trying to accomplish.

\[gallery size="large" columns="1" link="file" type="slideshow" ids="158,159,160,161,162,163,164,165,166"\]

Droplet should be generally available as early as the end of this month but it's early days yet: The first version will only support a single app in a single container. The plan is to support multiple apps in a container and even multiple containers in the future.

I anticipate that the product focus will be on the enterprise market, in order to help business organizations provide employees with the apps they want or need regardless of the device they use. Since this is all browser based, that appears a likely possibility. For Chromebook users though, this could open up a wide range of app support since Chrome OS is a browser-centric platform.

Sure, you can run Android apps on many Chromebooks today but these are mobile apps that may not have the full functionality of their native desktop counter parts. Plus, they were designed for small screens with touch input. And while there are web-based versions of many desktop apps, they typically require a network connection. Droplet can potentially overcome both of those challenges by providing the full-featured desktop apps that work offline thanks to browser caching.

For more information the benefits of WebAssembly, have a look at this video presentation of the technology from Google I/O 2017; there's a fantastic demo of a high-performing video editor that runs right in the browser around the 28:30 mark.

\[embed\]https://youtu.be/6v4E6oksar0\[/embed\]

---
title: "Project Crostini for Chromebooks explained in 15 minutes (video)"
date: "2018-04-23"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chromebooks"
  - "crostini"
  - "linux"
  - "pixelbook"
  - "productivity"
coverImage: "Project-Crostini-Sublime-Text-installed-scaled.png"
---

Last week, I demonstrated how to use Google's [Project Crostini to run full Linux apps](https://www.aboutchromebooks.com/news/first-look-running-full-linux-apps-on-a-chromebook-with-project-crostini/) on my Pixelbook. The technology is coming soon -- I fully expect detailed news and a general release at Google I/O next month -- but my shared experience doesn't cover much on how Google is accomplishing this.

This video, from a GDG event presentation last month, helps explain both what Project Crostini is and how it works.

\[embed\]https://youtu.be/aPDchQdhdTs\[/embed\]

A few takeaways if you don't have 15 minutes to watch the presentation:

- Linux containers in Chrome OS aren't the same as full virtual machines, which virtualize hardware as well as software.
- Android apps on Chrome OS already run in containers, so Google is extending this technology using a solution it already has.
- Containers will reportedly install as Chrome Extensions. This is the first I've heard this and I'm not sure if it's accurate. However, it may make sense from a usability standpoint if an extension can run a script to install a Linux app without the user accessing a command line.
- Google may enable full VM support on Chromebooks in the future based on [crosvm code](https://chromium.googlesource.com/chromiumos/platform/crosvm/), although my interpretation of crosvm is that it still won't emulate hardware; that could make development with Android Studio a challenge if you can't emulate a test device.

I'll continue to monitor Project Crostini developments through Google I/O, so stay tuned.

---
title: "Project Crostini Linux files now automatically mount in Chrome OS Files app"
date: "2018-05-24"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "crostini"
  - "dev-channel"
  - "files"
  - "linux"
  - "project-crostini"
coverImage: "Linux-files-mounted-in-Chrome-OS-Files.png"
---

I just noted that [Dev Channel version 68.0.3437.0 fixes the broken Terminal app](https://www.aboutchromebooks.com/news/dev-channel-update-68-0-3437-0-fixes-terminal-app-for-project-crostini/) for Project Crostini and thanks to DennyL, I found out that the Linux files automatically mount to the Chrome OS Files app in this version as well. That means no more [workarounds using the SSH app](https://www.aboutchromebooks.com/how-to/how-to-mount-linux-container-files-in-the-chrome-os-files-app-for-project-crostini/)!

I didn't see this at first for one reason: There's a flag to enable the feature. Make sure you type _chrome://flags_ in your browser and then enable the _#crostini-files_ flag. Restart and you should see a new Linux Files mount in the Files app on your Chromebook. Thanks DennyL!

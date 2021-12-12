---
title: "Linux apps are getting their own folder in the Chrome OS app launcher"
date: "2018-07-02"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "crostini"
  - "linux-apps"
  - "productivity"
  - "project-crostini"
coverImage: "Chrome-OS-App-Launcher.png"
---

Add another nice to have feature coming to Project Crostini: There will be a [dedicated folder for Linux apps in the Chrome OS app launcher according to this code change](https://chromium-review.googlesource.com/c/chromium/src/+/1103429) in the works. The title of the code change says it all: "Create crostini app folder and add all Crostini apps to it."

Interestingly, an explanatory comment in the change request indicates that existing Linux apps won't be moved into this dedicated folder, so there may be a little manual work on the part of folks who installed Linux software prior to this change.

> I have tested this update on hardware and it does not cause breaks with existing apps. They will not be moved to the folder, but the users can move them in if they wish.

However, going forward, I'd expect all newly installed Linux apps to automatically be added to the folder.

The change is part of making Linux apps on Chromebooks appear to be more native: In the early days of [Project Crostini](https://www.aboutchromebooks.com/tag/project-crostini/) -- just a few months ago -- we didn't even have app shortcuts at all. Instead, you'd have to launch your Linux software from a command line terminal in most cases. Then we got app shortcuts to ease the process.

Once this code change makes its way through testing and implementation, there should be a single folder in the Chrome OS app launcher that contains start-up shortcuts for these apps in one central, easy to find, location. Progress!

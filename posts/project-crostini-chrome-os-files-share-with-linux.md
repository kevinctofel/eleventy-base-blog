---
title: "Chrome OS Files app getting a \"Share with Linux\" option for Project Crostini"
date: "2018-09-24"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "crostini"
  - "files"
  - "files-app"
  - "linux"
  - "productivity"
  - "project-crostini"
coverImage: "Chrome-OS-Files-app-v70.png"
---

Running [Linux through Project Crostini](https://aboutchromebooks.com/tag/project-crostini) on a Chromebook is great although it brings some confusion and inefficiency when it comes to file management. While you can view data files from the Linux container in the Chrome OS Files app, it's not quite as easy the other way around. To mitigate this, [a new "Share with Linux" menu option will be in the Chrome OS Files application](https://chromium.googlesource.com/chromium/src/+/479efc9a8f5b0afc1cd06e68c0fa041b17dd9c4b).

Here's a description of the work-in-progress feature, [spotted by DennisLfromGA](https://www.reddit.com/r/Crostini/comments/9hv2qi/what_is_this_sm_cb_pro/), one of the  moderators of the Crostini sub-Reddit group :

> CrOS FilesApp: Crostini shared path management
> 
> New JS class Crostini to manage crostini shared paths. Record paths that are shared, and do not show 'Share with Linux' option for paths that are already shared.

To be clear, the "[Share with Linux](https://chromium-review.googlesource.com/c/chromium/src/+/1195406/10/ui/file_manager/file_manager/test/js/strings.js)" option won't appear for individual files but instead for directories, i.e.: folders. And based on the [most recent testing scripts](https://chromium.googlesource.com/chromium/src/+/479efc9a8f5b0afc1cd06e68c0fa041b17dd9c4b%5E%21/#F3), you won't be able to share the full Downloads folder in Chrome OS, nor any folders outside of the Downloads folder.

If you want your Linux container to see any Chrome OS files then, they'll have to be in a sub-folder of the Downloads directory on your Chromebook.

Assuming this feature makes its way through testing and deployment, it's a small but potentially very useful function. As it stands now, I've been manually moving data files and folders from Chrome OS to my Linux container through drops and drags in the Files app. That gets pretty tedious over time, so a simple yet secure, sharing mechanism will be welcomed.

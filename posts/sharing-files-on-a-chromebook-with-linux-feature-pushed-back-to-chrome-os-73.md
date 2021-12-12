---
title: "Chromebook file sharing with Linux feature pushed back to Chrome OS 73"
date: "2018-12-07"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chrome-os-73"
  - "dev-channel"
  - "files"
  - "linux"
  - "project-crostini"
coverImage: "Share-folder-with-Linux.png"
---

Well, this is a bummer, although I understand the reasoning. Last month, a new feature arrived in the Dev Channel of Chrome OS 72 to [support sharing local files with Project Crostini](https://www.aboutchromebooks.com/news/chrome-os-72-dev-channel-preps-crostini-usb-support-easier-linux-package-installs-and-more/), the function that brings Linux app support to Chromebooks. That feature is now disabled in the latest Dev Channel version, [which landed today](https://chromereleases.googleblog.com/2018/12/dev-channel-update-for-chrome-os.html) Don't worry, it's coming back with Chrome OS 73, or at least that's the plan.

What's the reason? It's pretty simple really. [According to the Chrome bug tracker](https://bugs.chromium.org/p/chromium/issues/detail?id=911861), the "backend features are not yet ready for M72."

That's actually a bit obvious if you've enabled the Share with Linux flag, which is found at _chrome://flags/#crostini-files._ Enabling that flag does add a "Share with Linux" menu in the native Files app, but it never actually showed the files to you in the Linux container. Or if it did, I never saw where they were.

There was (or is if you didn't yet get the new version of the Dev Channel) a setting to manage these shared filed and folders but it doesn't show the contents of them. Instead, it simply allows you to remove the sharing between Chrome OS and Linux for the files and folders of your choice [![](images/Manage-shared-Linux-folders-1024x402.png)](https://www.aboutchromebooks.com/news/project-crostini-linux-apps-new-features-fixes-in-chrome-os-71-dev-channel/attachment/manage-shared-linux-folders/)

Clearly, then there's work to be done on the Project Crostini side, so the development team is likely disabling the feature while they get that work done. It appears to me from reading the code change that the flag to enable file sharing isn't going away. Instead, even if you have it enabled, Chrome OS will override the setting to disable it behind the scenes.

Of course, you can always [access, move or copy files and folders between Chrome OS and Linux from within the Files app](https://www.aboutchromebooks.com/news/chrome-os-files-app-changing-again-to-better-integrate-local-android-and-linux-files/).

I created a Downloads folder in my Project Crostini home directory and if I ever want to use a Chrome OS file in Linux, I just copy it there in the Files app for example. Sharing files can be more effective, or even required for some activities, such as app development, or [easier installation of Linux packages](https://www.aboutchromebooks.com/news/how-to-install-debian-linux-packages-in-project-crostini-chrome-os-files-app/), so it's still an important feature for Chrome OS. It simply isn't ready quite yet.

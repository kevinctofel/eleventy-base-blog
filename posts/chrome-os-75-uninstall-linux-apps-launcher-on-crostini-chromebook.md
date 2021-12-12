---
title: "Chrome OS 75 will let you uninstall Linux apps from the launcher on your Chromebook"
date: "2019-03-07"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chrome-os-75"
  - "crostini"
  - "linux"
  - "linux-apps"
  - "productivity"
  - "project-crostini"
coverImage: "Linux-apps-in-launcher-1-scaled.jpg"
---

Currently, it's easy to uninstall either a Chrome web app, a PWA (Progressive Web App) or an Android app from a Chromebook: You can typically right click on the app in your Chrome OS launcher to see an "Uninstall" menu option. There's no such method to do this for installed Linux apps though. There will be.

Planned for the Stable channel of Chrome OS 75, the Chromium team has developed and tested the functionality for [Linux app uninstalls directly from the Chrome OS launcher](https://bugs.chromium.org/p/chromium/issues/detail?id=909071). That will bring a consistent user experience for all app uninstalls and also make Linux use a wee bit less daunting for mainstream users - you can already [install Linux packages natively from the Chrome OS Files app](https://www.aboutchromebooks.com/news/chromebooks-project-crostini-install-debian-apps-packages-in-chrome-os/), for example, providing those are Debian packages.

For now, uninstalling a Linux app requires you to have a little knowledge of terminal commands. While that's useful for those who have that knowledge, folks that don't may not know how to uninstall a Linux app on a Chromebook.

![](https://i2.wp.com/www.aboutchromebooks.com/wp-content/uploads/2019/03/uninstall-chromium-linux.png?fit=800%2C241&ssl=1)

We first saw [mention of this feature back in October](https://www.aboutchromebooks.com/news/project-crostini-linux-app-uninstall-functionality/) and the underlying code is ready to go, save for one small issue: For some reason, there's a current bug for Emacs not installing properly. The team was ready to flip the uninstall flag for Chrome OS 74 but decided to [hold up until the Emacs bug is fixed](https://bugs.chromium.org/p/chromium/issues/detail?id=822514#c28), so the target date has been pushed to Chrome OS 75.

Note that if you _manually_ created a desktop icon for a Linux app, this new functionality won't be there. For those situations, you'll still need to use the Linux terminal; chances are though, if you know how to create a desktop icon for a Linux app you very likely know how to manually uninstall that app from the Terminal.

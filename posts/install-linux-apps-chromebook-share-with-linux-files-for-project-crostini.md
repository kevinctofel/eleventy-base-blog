---
title: "Chrome OS \"Share with Linux\" feature will make it easier to install Debian apps in Crostini"
date: "2018-10-30"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "crostini"
  - "debian"
  - "files-app"
  - "linux"
  - "linux-apps"
  - "productivity"
  - "project-crostini"
coverImage: "Visual-studio-being-installed.png"
---

Last month, we found out that [Chrome OS is getting a nifty "Share with Linux" feature in the native Files app](https://www.aboutchromebooks.com/news/project-crostini-chrome-os-files-share-with-linux/). With it, you can share any local folder on your Chromebook with a Linux container in Project Crostini. That functionality will bring an additional benefit in an upcoming Chrome OS release: [An easier way to install Debian apps](https://www.aboutchromebooks.com/news/chrome-os-will-show-debian-package-details-when-installing-in-the-files-app/).

The way Crostini works today requires you to move any downloaded .deb packages manually from Chrome OS to your Linux container. With Chrome OS 72, you won't have to do that. Instead, you can simply share a Chrome OS folder -- say your Downloads folder -- with the Linux instance and right-click on any downloaded packages to choose the installation option.

> CrOS FilesApp: allow install deb by sharing with crostini
> 
> Currently deb files can only be installed into the crostini container in FilesApp if they are already in Linux files.
> 
> Now, files will be shared with the container if they are in a sharable volume such as Downloads or Drive, so deb files at these locations can be installed.

Interestingly, the comment above also mentions shared Drive folders. Yup, that's coming too as reported last week: You'll be able to [share folders from Google Drive, Team Drives and Computers that you've set up to sync with Drive](https://www.aboutchromebooks.com/news/project-crostini-share-google-drive-team-drives-computer-linux-chromebook/).

Essentially, you'll be able to store Debian packages up in the cloud on your Google Drive and have them sync down to a Chromebook, like any other Drive files or folders. Or you can simply download them in the Chrome browser on your Chromebook. And then, using the native Chrome OS Files app, you can right-click them for installation in the Linux container without moving them to the Linux file system.

Removing a single manual step might seem like a small thing, but it will save time and improve the user experience for and more integrated Linux app install process on a Chromebook. I love it: Users shouldn't really have to worry about where the installation file is for a package.

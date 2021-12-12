---
title: "Audio playback for Linux on Chromebooks arrives in latest Chrome OS 74 Dev Channel release"
date: "2019-02-26"
categories: 
  - "news"
tags: 
  - "audio"
  - "chrome-os"
  - "chrome-os-74"
  - "crostini"
  - "dev-channel"
  - "linux"
  - "music"
  - "project-crostini"
coverImage: "Pixel-Slate-performance-e1550596979368-scaled.jpg"
---

[Google released version 74.0.3713.0 to the Chrome OS 74 Dev Channel](https://chromereleases.googleblog.com/2019/02/dev-channel-update-for-chrome-os_25.html) on Monday and there are over 500 mentions of "Crostini", the project that brought Linux support to Chromebooks. I'm still poring through the changelog, but I immediately noticed a mention of audio support. I tested it, and after a few commands in the Terminal as well as a few reboots, I got it to work.

As I reported last week, the official container documents for Chrome OS were updated to [reflect audio support in version 74](https://www.aboutchromebooks.com/news/chrome-os-74-audio-playback-support-linux-on-chromebooks-project-crostini/). You may want to refer [to that document](https://chromium.googlesource.com/chromiumos/docs/+/master/containers_and_vms.md#Is-audio-output-supported) because there are some commands I needed to get sound out of my Pixel Slate on the Dev Channel.

Specificially, I had to run through these:

\# Make sure the new cros-pulse-config package is installed.   
$ sudo apt-get update   
$ sudo apt-get dist-upgrade   
\# Clear out existing pulse settings.   
$ rm -rf ~/.config/pulse   
\# Turn it off & on again via crosh (Ctrl-Alt-T).   
crosh> vmc stop termina

Initially, I didn't hear any test sounds after executing these commands; I threw a reboot in after the last command and finally got audio playback in Linux.

Here's a brief look -- well, a listen -- to the weekly podcast I do as played back in the Chromium browser running in the Linux container.

I'll continue to scour through the latest Dev Channel release notes for additional features, so stay tuned. And in the meantime, enjoy audio in your games, websites and music players in Crostini if you're on the Dev Channel. Keep in mind that the Dev Channel is still buggy and if you decide it's not for you, reverting to a lower version of the Beta or Stable channel can remove all of the data and apps on your Chromebook.

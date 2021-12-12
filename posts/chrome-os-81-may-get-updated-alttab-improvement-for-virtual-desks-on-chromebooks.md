---
title: "Chrome OS 81 may get updated Alt+Tab improvement for Virtual Desks on Chromebooks"
date: "2020-03-25"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chrome-os-81"
  - "chromebooks"
  - "keyboard-shortcuts"
  - "productivity"
  - "virtual-desks"
coverImage: "Chrome-OS-virtual-desks-workspaces-scaled.png"
---

[Virtual desks, introduced in the Stable Channel of Chrome OS 78](https://www.aboutchromebooks.com/news/chrome-os-78-stable-channel-arrives-heres-what-you-need-to-know/), have gotten a ton of feedback. Most of it is good but there have been a growing number of Chromebook users not happy with the _Alt-Tab_ keyboard combination.

Why? Because _Alt-Tab_ doesn't switch between active apps on a single virtual desktop workspace on a Chromebook. Instead, it currently moves between apps on _all_ virtual desks.

The feedback has been heard and [today Google introduced a code option to limit Alt-Tab behavior to only the currently active virtual desk](https://bugs.chromium.org/p/chromium/issues/detail?id=1023445#c17).

The new keyboard combination option will initially be/ hidden behind a flag, so you'll need to enable it at _chrome://flags#ash-limit-alt-tab-to-active-desk_ when it arrives. The change was just submitted for a merge request a short while ago with this comment on when to expect it:

> We are still considering the long term design of this behavior, but in the meantime, we're exposing a \`chrome://flags\` flag to enable limiting Alt-Tab windows to the current active desk. The flag will be disabled by default. We intend to attempt merging back this change to M-81.

As I noted earlier this week, Chrome OS 81 will be the next major release for Chromebooks in the near future. [Chrome OS 82 will be skipped](https://www.aboutchromebooks.com/news/chromebooks-skip-chrome-os-82-due-to-covid-19/) and the release date for Chrome OS 83 is currently a moving target.

When Google decided to pause Chrome OS releases, the Chrome Engineering team said it would focus changes for Chrome OS 81 on security updates, so it appears that the team is making an exception for this feature request. I can definitely appreciate that and I'm sure those who submitted feedback do too.

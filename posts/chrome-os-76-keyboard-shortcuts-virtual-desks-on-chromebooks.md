---
title: "Chrome OS 76 adds keyboard shortcuts to virtual desks on Chromebooks"
date: "2019-06-28"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chrome-os-76"
  - "keyboard-shortcuts"
  - "productivity"
  - "virtual-desks"
coverImage: "Virtual-desks-Chrome-os-77-1-scaled.png"
---

While tracking the upcoming [virtual desks feature for Chrome OS](https://www.aboutchromebooks.com/tag/virtual-desks/), everything has looked good.

[Need up to four virtual desktops](https://www.aboutchromebooks.com/news/video-virtual-desks-workspaces-chrome-os-74-chromebooks-tablets/)? Check.  
Want to move an app from one workspace to another? Check.  
Hope to have [virtual desks in Chrome OS 76](https://www.aboutchromebooks.com/news/chrome-os-76-bringing-virtual-desktops-to-chromebooks/) and not wait until Chrome OS 77? Check.

But the one thing that's been "missing", or at least heavily requested is to have keyboard shortcuts available for navigating through multiple apps on multiple virtual desks.

You can check that one off too, now that they've been added to this feature.

On Thursday, this code commit was added to include the following keyboard shortcuts for virtual desks:

- **Ctrl+Search + =** Adds a new desk.
- **Ctrl+Search + -** Removes a desk.
- **Ctrl+Search + \]** Activates a desk on the right (if any).
- **Ctrl+Search + \[** Activates a desk on the left (if any).
- **Ctrl+Search+Shift+\]** Moves an active window (or highlighted window in overview mode) to a desk on the right (if any).
- **Ctrl+Search+Shift+\[** Moves active window (or highlighted window in overview mode) to a desk on the left (if any).

I haven't yet tested the keyboard shortcuts; in fact, the Chromium team has just added their own internal tests for them. And since this is code in progress, the actual keyboard shortcut combinations may change. Then again, there are already [numerous Chrome OS keyboard shortcuts, so the options are becoming fewer and farther](https://www.aboutchromebooks.com/how-to/how-to-get-the-old-on-screen-chrome-os-keyboard-shortcuts-back/) between. ;)

Still, this is the one key element that, up to now, has been widely hoped for, mainly because without it, virtual desks would rely solely on a touch interface. That's not ideal user experience for all Chromebook users, nor would it be the quickest.

If you haven't yet seen the latest look at how virtual desks on Chromebooks work, here's a short demo I captured when using the feature earlier this month on Chrome OS 77. Note that virtual desks are actually in Chrome OS 76 and the feature flag is disabled by default.

https://youtu.be/6EoXhfruZL4

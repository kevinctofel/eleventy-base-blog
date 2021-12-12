---
title: "You'll be able to resize your Linux drive space on Chromebooks, likely in Chrome OS 75"
date: "2019-03-06"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chrome-os-75"
  - "crostini"
  - "linux"
  - "project-crostini"
coverImage: "Crostini-container-file-sizes-e1551866796633-1-scaled.jpg"
---

I recently learned that when you enable Linux on a Chromebook using the [Crostini function](https://www.aboutchromebooks.com/tag/project-crostini), Chrome OS allocates a maximum of 90 percent of your free disk space for the Linux container. On my Pixel Slate with 128 GB of local storage, that leaves me lots of room for Linux usage.

Running a _df -h_ command in my Linux terminal (shown above) shows that my container has plenty of potential room, also leaving enough space -- so far -- for my regular Chrome OS usage.

But what about Chromebooks that have very little local storage to begin with, say 16 GB. And what happens when someone enables Linux on a Chromebook where they have little free storage available due to long time usage and many downloaded files?

Those latter situations could lead to a very small file system workspace for the Linux container, so [the Chromium team has been developing a way to resize the container after it has been created](https://bugs.chromium.org/p/chromium/issues/detail?id=858815):

> Currently we just set the maximum size the disk image can have to 90% of the free space available when crostini is initially installed. There has been talk of finding ways to allow this cap to be increased after installation or overcommitting free disk space to avoid leaving the user with an excessively small disk image.

Initial work is on expanding the disk size, mainly because that's relatively easier than shrinking it. And the resize function will likely be a manual process at first, with plans to add some automatic behavior in the future, per this comment:

> Currently, there is no automatic policy for resizing disks - that will  
> be implemented in another change.

The bug report for this feature was first filed in November and over the past few weeks, many code changes have been implemented to support disk resizing.

Chrome OS 73 was the original target for disk resizing, but the feature freeze date was back on January 11 for that release. In fact, we're past the freeze for Chrome OS 74 as well, so I anticipate this to be a Chrome OS 75 addition, with [that Stable release expected on June 11](https://chromiumdash.appspot.com/schedule).

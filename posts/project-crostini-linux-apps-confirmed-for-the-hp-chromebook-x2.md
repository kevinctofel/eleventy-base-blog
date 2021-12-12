---
title: "Project Crostini (Linux apps) confirmed for the HP Chromebook X2"
date: "2018-06-13"
categories: 
  - "news"
tags: 
  - "chromebooks"
  - "crostini"
  - "hp"
  - "hp-chromebook-x2"
  - "linux"
  - "project-crostini"
coverImage: "HP_Chromebook_x2_FrontRight_Detached-1-scaled.jpg"
---

The latest (and only) detachable Chromebook, [the HP Chromebook X2](https://www.aboutchromebooks.com/news/hp-chromebook-x2-arrives-as-the-first-detachable-chromebook-tablet/), is likely to be among the next devices to get support for Project Crostini, which will enable [full Linux app support](https://www.aboutchromebooks.com/tag/crostini/). Thanks to [a code commit spotted by Redditor cygnus8595](https://www.reddit.com/r/Crostini/comments/8qvbt5/new_commit_for_poppy_baseboard_hp_chromebook_x2/), we have confirmation of this development.

The [commit, posted on June 12](https://chromium-review.googlesource.com/c/chromiumos/overlays/board-overlays/+/1097708), is pretty explicit:

> This change turns on the kvm\_host USE flag so that we can run VMs on poppy/soraka.

Wait, where's the mention of the HP Chromebook X2, you ask? It's all in the last two words of the commit.

Poppy is the codename for a baseboard; Google uses these boards to give device makers a certified working Chrome OS reference to build from. And if you look at the official [Developer Information for Chrome OS Devices page](https://www.chromium.org/chromium-os/developer-information-for-chrome-os-devices), you can see which devices are built from which boards (shown below). Right now, only the HP Chromebook X2 is a Poppy board and we also know that the X2's device code name is Soraka:

[![HP Chromebook X2 poppy](images/HP-Chromebook-X2-poppy.png)](https://www.aboutchromebooks.com/wp-content/uploads/2018/06/HP-Chromebook-X2-poppy.png)

There's no timeline on when to expect Crostini support on the HP Chromebook X2, but if I had to guess, I'd say Dev Channel 69 at the earliest, which should be here by the end of this month.

As exciting as this is, I'm [sticking with my Pixelbook even though the HP Chromebook X2](https://www.aboutchromebooks.com/opinion/pixelbook-or-hp-chromeook-x2-detachable-chrome-tablet/) will have the same functionality. My reason? The $599 HP model only comes with 4 GB of memory and I'm leery of how well Linux apps -- or at least the ones I use -- will run with that amount of RAM compared to the 8 GB of memory in the base Pixelbook. Perhaps I'll be surprised when someone gets to test Linux apps; in which case, maybe I'll change my mind.

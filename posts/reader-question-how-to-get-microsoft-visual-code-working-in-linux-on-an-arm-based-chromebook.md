---
title: "Reader question: How to get Microsoft Visual Code working in Linux on an ARM-based Chromebook"
date: "2019-03-19"
categories: 
  - "how-to"
  - "news"
tags: 
  - "arm"
  - "chrome-os"
  - "crostini"
  - "developers"
  - "linux"
  - "linux-apps"
  - "productivity"
  - "project-crostini"
coverImage: "Visual-Code-installed-scaled.png"
---

Terry wrote to me to see if there was a way to get a good code editor for programming on his Chromebook. [I use several of them thanks to Linux support on my Pixel Slate](https://www.aboutchromebooks.com/news/how-to-code-on-a-chromebook-crostini-pixel-slate/), but Terry has a Samsung Chromebook Plus. That means he needs Linux packages compiled for the ARM processor in his device. Here's his full email, which I'll follow up with a solution and some thoughts.

> Currently, I am in search of a good IDE that I could run locally. I have tried to download both Atom and Visual Code and I see that installs are only amd64 compatible. I presume I need an arm64 distribution for my Samsung Chromebook Plus.  

Terry is correct: He can't simply install the x86 version of a Linux app like I can because of the different chip architectures. But, luckily, there's a solution in his case.

An effort by [Jay Rodgers to provide community builds of Visual Code for arm64 is available here](https://code.headmelted.com/). Note that this is not an official, Microsoft-built package because Microsoft isn't supporting the software for arm64. However, it is built from [the official source code](https://github.com/Microsoft/vscode), as Visual Code was open sourced in 2015

So Terry -- or anyone else on an ARM-based Chrome OS device that wants to run Visual Code -- can simply [download the most recent Visual Code package here](https://github.com/headmelted/codebuilds/releases). The alternative would be to build the package yourself from source, but.... why bother? ;)

Unfortunately, I haven't found an error-free version of Atom for arm64, but [many folks have been looking into it for some time](https://github.com/atom/atom/issues/15881). Terry also had an interesting question about ARM64 support:

> I would be curious to learn if and when an arm64 version of these tools might be made available.  If that is unlikely, it would also be interesting to know why it is unlikely to happen. Would the Chromebook user base be large enough to prompt a new distribution of these tools?

My thought is that since most Chromebooks run on Intel x86 processors, as well as some [newer ones using AMD chips](https://www.aboutchromebooks.com/news/acer-chromebook-315-amd-radeon-r4-specs-price-availability/), this general software situation isn't likely to change any time soon, if at all.

There will always be community-focused developers that provide builds from open source software as Jay does, but the software companies themselves aren't likely to see a need for arm64 compatibility anytime soon. And even if they want to, there are often underlying dependencies that could prevent it: Luckily, Electron -- used for Visual Code -- [can be built for arm64](https://electronjs.org/docs/development/build-instructions-linux).

I'd like to be wrong on that assessment but given the current market state, I don't think I am, or at least will be for several years. Agree or disagree?

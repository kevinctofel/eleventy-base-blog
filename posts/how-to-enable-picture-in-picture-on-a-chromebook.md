---
title: "How to enable Picture-in-Picture on a Chromebook (updated)"
date: "2018-05-14"
categories: 
  - "how-to"
tags: 
  - "chrome-os"
  - "dev-channel"
coverImage: "Chrome-OS-PiP.png"
---

At Google I/O last week, the company showed off a ton of Chrome OS developments ranging from [Linux app support](https://www.aboutchromebooks.com/news/google-officially-unveils-project-crostini-linux-apps-on-chrome-os/), a [Chrome OS emulator in Android studio](https://www.aboutchromebooks.com/news/google-adds-a-chrome-os-emulator-to-android-studio/) and a workaround to [mount Linux files in a Chrome OS container](https://www.aboutchromebooks.com/how-to/how-to-mount-linux-container-files-in-the-chrome-os-files-app-for-project-crostini/). Picture in Picture support has also been in the works for months and [Chrome Unboxed showed off an early look at the feature](https://chromeunboxed.com/first-look-picture-in-picture-mode-for-chrome/).

Google's "Happiness Evangelist", [François Beaufort recently updated his Git repository](https://github.com/beaufortfrancois/picture-in-picture-chrome-extension) to make it easy for any Chromebook or Chromebox running Chrome OS version 68 (currently in the Dev Channel) to demo this feature.

You'll first need to enable these flags by typing _chrome://flags,_ followed by the flags below, in your browser:

- #enable-experimental-web-platform-features
- #enable-surfaces-for-videos
- #enable-picture-in-picture

Once these are enabled, [download this special Picture-in-Picture extension](https://github.com/beaufortfrancois/picture-in-picture-chrome-extension/archive/master.zip), and extract the zip file on your Chrome OS device.

Next, type _chrome://extensions_ in your browser and toggle and look for the Developer Mode option at the top right. Toggle it on and then click the Load Unpacked option. Navigate to and choose the **/src** folder in the unzipped extension file to add the PiP extension and you're done.

Now, whenever you watch video in your Chrome browser, you can tap the newly installed PiP extension to break the video out to its own floating, re-sizable window that's always on top of other windows. While this implementation currently uses an extension, Google could certainly choose to make this feature a native function in Chrome OS so it would be available without any of these installation steps.

[![](images/Watching-Parts-Unknown-in-PIP.png)](https://www.aboutchromebooks.com/wp-content/uploads/2018/05/Watching-Parts-Unknown-in-PIP.png)

Either way, I'm thrilled to test and use Picture in Picture on my Pixelbook: I stream all of my television content from Sony PlayStation VUE and now that they [support streaming in a Chromebook browser](https://www.aboutchromebooks.com/news/you-can-now-watch-sony-playstation-vue-on-a-chromebook-in-the-browser/), I can watch live sports and DVR content while working.

_**Update**: As of June 6, this feature isn't currently available; it appears Google has pulled the functionality. If and when it returns, this post will reflect availability in an another update._

---
title: "Don't expect to sideload Android apps on a Chromebook until Chrome OS 76 or later"
date: "2019-05-20"
categories: 
  - "news"
tags: 
  - "android"
  - "android-apps"
  - "android-studio"
  - "chrome-os"
  - "chrome-os-75"
  - "chrome-os-76"
  - "developer-mode"
  - "developers"
  - "sideloading"
coverImage: "Unknown-sources-Android-settings-Chrome-OS-1-1-scaled.jpg"
---

Unless you want to [put your Chromebook in the less secure Developer Mode](https://www.aboutchromebooks.com/qa/whats-the-difference-between-developer-mode-and-the-dev-channel-on-a-chromebook/), you don't have access to sideload Android apps to your device. That's because the option to allow Android installations from anywhere other than the Google Play Store can't be enabled.

Over the past six months, I saw some effort from the Chromium dev team on this but lately, not so much. In fact, [a recent comment from one of the developers](https://bugs.chromium.org/p/chromium/issues/detail?id=761329#c55) suggests that even though the original plan was to [support sideloaded apps between Chrome OS 69 and 72](https://bugs.chromium.org/p/chromium/issues/detail?id=761329#c35), it's happening anytime soon:

> I don't expect this will be available in the M-75 release.

I'm running Chrome OS 76 Canary Channel on a device and this functionality isn't supported there either. My guess? Unless there's a flurry of activity in the next month or so, this will get pushed beyond Chrome OS 76 as well.

While some non-developer Chromebook owners want this feature, I think there's another focused audience as well: Android app developers using Chromebooks.

![Chrome OS emulator on Android Studio](images/Chrome-OS-emulator-on-Android-Studio-1-1024x683-1.jpg)

Chrome OS and Android emulation

Why? Because the current preview of [Android Studio for Chrome OS](https://www.aboutchromebooks.com/news/android-studio-chrome-os-chromebook-recommendation-google-io-2019/), which is now in Beta 2, doesn't support any Android app emulation at all: Not for Chrome OS devices, nor for Android devices. Instead, a developer has to connect an Android phone or tablet with a USB cable to the Chromebook and push the app over.

I did this over the weekend with a small app I'm creating and it works fine, but it's not ideal due to the many different Android devices on the market. And it doesn't tell a developer _anything_ about how their app will run on Chrome OS, which is part of the reason for getting Android Studio on Chromebooks to begin with.

For now, we wait. Is the ability to sideload Android apps on your Chromebook something you're looking forward to, or is it just me? Let me know in the comments!

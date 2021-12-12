---
title: "Chrome OS 91 will add notification badges to PWAs on Chromebooks"
date: "2021-03-14"
categories: 
  - "news"
tags: 
  - "chrome-os-91"
  - "flags"
  - "productivity"
coverImage: "progressive-web-app-badges.jpg"
---

The Chrome desktop browser has supported [notification badges on Progressive Web Apps (PWAs) since release 73](https://www.chromestatus.com/feature/6068482055602176). Unfortunately, Chromebook users still don't have this feature. That's slated to change in the next few months, however: Chrome OS 91 will add notification badges to [PWAs on Chromebooks](https://www.aboutchromebooks.com/tag/progressive-web-apps/).

While browsing around the latest Chromium code commits, I happened upon [this design document](https://chromium-review.googlesource.com/c/chromium/src/+/2748138) for the feature, which says the target release is Chrome OS 91. Checking the [Chromium release calendar](https://chromiumdash.appspot.com/schedule "https://chromiumdash.appspot.com/schedule"), I see that we can expect the Stable Channel of Chrome OS 91 to land around June 1. So we're a ways off yet from seeing this feature.

Once it lands, you can expect your Chromebook to show badges on installed PWA icons, similar to how these appear on mobile app icons on your phone.

According to the Badging API documentation currently in use on Chrome, here's a description:

> Allows web apps (as defined by the Web App Manifest standard) to set an app-wide badge in operating-system-specific places such as the shelf or home screen. Additionally, it gives the app a small, visible place to notify the user of new activity that might require attention, without showing a full notification. It can show additional information, such as an unread count or event type. It allows the app to convey this information when its windows are closed.

Personally, I like badging on icons more than notifications, which can be intrusive. Without taking any of my focus away from what I'm doing, I get a quick indication that something needs attention in an app. Based on the app, I can then decided to address it immediately or put it off until a later time.

Of course, the Canary, Dev and Beta Channels will see this an an experimental feature long before the Stable Channel of Chrome OS 91. As such, there will be flags to enable it in advance for testing. Stay tuned as I'll share them once they go live in a pre-Stable Channel release.

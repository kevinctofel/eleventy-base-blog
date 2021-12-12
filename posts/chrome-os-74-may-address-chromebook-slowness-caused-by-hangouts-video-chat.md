---
title: "Chrome OS 74 may address Chromebook slowness caused by Hangouts video chat"
date: "2019-04-08"
categories: 
  - "news"
tags: 
  - "bugs"
  - "chrome-os"
  - "chrome-os-74"
  - "hangouts"
  - "productivity"
  - "video-chat"
coverImage: "hangouts-chrome-os.jpg"
---

There's an [interesting bug report for Chrome OS named "Hangouts video chat can cause slowness / jank"](https://crbug.com/947577) filed about 10 days ago and getting some developer attention today. Well, it's interesting to me because I often use Hangouts to video chat with some of my business partners.

I haven't personally experienced this issue, but you can see the reported problem in this video taken by a member of the Chromium team for debugging purposes:

Various users reported an unusable Hangouts video client, app freezing and general slowness in Hangouts; the latter is easily seen in the above video when typing a chat message after starting a video call, for example. Maybe that's why I haven't experienced the problem since I generally use video or chat in Hangouts, but not both simultaneously.

Regardless, the Chromium team is looking into this and have bounced the priority back and forth between a zero and a one; zero being a top priority.

Based on telemetry logs and research, the problem appears related to either the graphics driver, high CPU load or perhaps both. Luckily, the team is researching the root cause and is currently targeted for a Chrome OS 74 fix.

> In the feedback report I see kernel hang inside the graphics drm driver from the previous reboot.
> 
> As for the slowness, but not hang, I can see that the system was extremely busy. The camera service was having hard time to keep up the camera frame delivery.

Have you seen or experienced this issue in Hangouts? If so, which device and hardware configuration do you have? Maybe we can help get a fix for the Hangouts jank.

---
title: "Chrome OS may add extra security to view passwords saved in a Google account"
date: "2019-01-17"
categories: 
  - "news"
tags: 
  - "2fa"
  - "chrome-os"
  - "google"
  - "passwords"
  - "security"
coverImage: "Google-Password-manager.png"
---

If you store your passwords natively with Google on a Chromebook, you have easy access to them once you're signed in to your device. Just visit Settings, Passwords in Chrome OS and you can see them all in a list or search for specific ones. There's no additional authentication required. That could change though: [Chrome Story found an active bug report that may add an additional sign-in step for authentication](https://www.chromestory.com/2019/01/enter-password-again-to-view-saved-passwords/).

That's actually how Google's password store works in the Chrome browser on all other platforms, so this would add consistency, per one of the [bug request](https://bugs.chromium.org/p/chromium/issues/detail?id=917178) comments:

> On Windows, MacOS, Android and iOS we ask the user to enter their OS credentials before revealing the password. On ChromeOS there is no API to do that (AFAIK). This did not make it to the password manager team's priority list because of the effort to introduce such a reauthentication mechanism.

I'm not overly concerned about my Google passwords currently being "unsafe" on a Chromebook because I always lock it when I'm not using it. And if someone had my Google account credentials already, they would have access to my passwords stored with Google simply by hitting [https://passwords.google.com](https://passwords.google.com) and signing in. Put another way: My Chromebook isn't the weak spot here. Plus I have two-factor authentication (2FA) enabled for my Google account anyway.

There still seems to be some internal debate on how to implement this change, as well as if it should apply specifically to enterprise users with managed Chrome OS devices via policy or it should become available to consumer users of Chrome OS as well.

> The feature request seems to be to have a policy that disables the reveal button in chrome://settings/passwords. For this, the enterprise team would be the most skilled people because they know how to introduce policies and make them affect things in chrome://settings.

I'd vote for both since an extra authentication wouldn't hurt anyone.

If the current Google account passwords situation scares you, there's always the option of a third-party password manager such as LastPass or 1Password. For now, I'm sticking with Google and keeping my 2FA setting on for the account.

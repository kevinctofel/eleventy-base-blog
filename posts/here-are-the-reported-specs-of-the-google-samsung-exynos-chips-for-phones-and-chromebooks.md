---
title: "Here are the reported specs of the Google-Samsung Exynos chips for phones and Chromebooks"
date: "2020-04-14"
categories: 
  - "news"
tags: 
  - "arm"
  - "chromebooks"
  - "exynos"
  - "google"
  - "samsung"
  - "soc"
coverImage: "Screenshot-from-2020-04-14-12-09-09.png"
---

There's lots of buzz today about [a new Axios report suggesting that Google is working with Samsung on a custom chip that could be used in Pixel phones and Chromebooks.](https://www.axios.com/scoop-google-readies-its-own-chip-for-future-pixels-chromebooks-e5f8479e-4a38-485c-a264-9ef9cf68908c.html) And that buzz is warranted as Google typically uses silicon that's generically available for its hardware, although with an occasional modification.

But there may be more details to the story as [I read about this rumored chip collaboration last week on SamMobile](https://www.sammobile.com/news/samsung-designing-custom-exynos-chipset-google/):

> ...Samsung seems to have even bigger plans for its Exynos chipsets in the future. Apparently, the company is developing a custom Exynos chipset in partnership with Google. According to a new report, the custom Exynos processor could be launched by Google as soon as this year.

I didn't share the news at the time because I really wanted to see either a second source confirming or some other details that could corroborate the report. I did some digging in the Chromium code commits but came up empty.

I trust the reporting of Axios on this one though, so here's a little more detail by way of a Korean forum; it's worth noting that Samsung is based in South Korea, although that fact alone doesn't confirm anything.

[According to the forum post](https://www.clien.net/service/board/cm_stock/14811926), these are the general specs for the Exynos chips that Google is partnering with Samsung on, codenamed "Whitechapel", per Axios:

- ARM octo-core SOC
- Dual-core A78 (not yet announced, likely based on "[Hercules](https://www.arm.com/company/news/2018/08/accelerating-mobile-and-laptop-performance)")
- Dual-core A76
- Quad-core A55
- MP20 GPU built on ARM's Borr architecture (unannounced)
- Google Visual Core and NPU (Neural Processing Unit)
- 5LPE process

Assuming the reported architecture specs are accurate -- and some of them line up with Axios' reporting -- this SoC could easily be used for a phone, more so than an ARM-powered Google-branded Chromebook.

However, we haven't seen much progress on Google using Qualcomm's ARM processors for Chromebooks of late: [Evidence of the Cheza reference device based on the Snapdragon 845](https://www.aboutchromebooks.com/news/cheza-chromebook-with-qualcomm-snapdragon-845-will-have-speedy-ufs-storage/) first appeared in 2018 but seems to have stalled.

So perhaps Google is still interested in its own ARM-based Chromebooks and might use a custom Exynos chip for one in the near future.

And with four high-power processor cores paired with four mid-range cores, a Chromebook built with the reported chip could approach mid-level performance, so it's possible.

Add in improved neural processing by Google for Assistant integration and maybe some intelligent app or site surfacing based on ML and it would be interesting to see.

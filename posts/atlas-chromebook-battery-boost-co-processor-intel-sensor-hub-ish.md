---
title: "Atlas Chromebook to get a battery boost with Intel Integrated Sensor Hub co-processor"
date: "2018-11-01"
categories: 
  - "news"
tags: 
  - "atlas"
  - "chrome-os"
  - "chrome-tablets"
  - "chromebooks"
  - "intel"
coverImage: "intel-chip.jpg"
---

I'm getting a few emails a week about the previously reported [Atlas Chromebook](https://www.aboutchromebooks.com/tag/atlas). Yes, it's still in the works, although I have no definitive information on an announcement date. I do have some additional information on Atlas, however: It will be among the first Chrome OS devices to include support for Intel's Integrated Sensor Hub (ISH), which the Chromium team is dubbing "\_ish" for short.

In fact, there's [a tweak to the Atlas board in the Chromium repository to reflect this](https://chromium-review.googlesource.com/c/chromiumos/overlays/chromiumos-overlay/+/1296030). Instead of Atlas being used I'm seeing references to Atlas\_ish, indicating that this is the Atlas board with the addition of the ISH. But what exactly does this mean?

At a high level, Atlas\_ish -- or any other board with the "\_ish" addition -- will have a lower-powered co-processor that handles sensor data. Think of it like any other device with a similar coprocessor, such as [Apple iPhones with their M-series chips](https://en.wikipedia.org/wiki/Apple_motion_coprocessors): These manage the sensor data and other low-power computing tasks to improve battery life.

Indeed, that's exactly what the Intel ISH will do for Atlas and likely other Chrome OS devices based on this snippet from [Intel ISH documentation, which  is here for the technically curious](https://www.kernel.org/doc/Documentation/hid/intel-ish-hid.txt):

> Intel Integrated Sensor Hub (ISH)
> 
> A sensor hub enables the ability to offload sensor polling and algorithm processing to a dedicated low power co-processor. This allows the core processor to go into low power modes more often, resulting in the increased battery life.

Will this technical solution add hours and hours of battery life to a device as compared to one not using a sensor hub? No, but I suspect it could eke out an extra 30 minutes or more, and when it comes to battery life on mobile devices, that's one of the largest challenges to overcome.

Sure, you could simply use a larger battery, but it comes at the sacrifice of weight, size, or both. Any battery boost without giving up other features is a win when it comes to hardware design. The integrated sensor hub runs on far less power than the main processor -- which is overkill for sensor data --  and can quickly wake when needed.

For the moment, I haven't found any other boards in development with the "\_ish" designation. It's likely that Atlas is the first and then that effort is applied to other boards that follow. And when Atlas does arrive, I'm betting that one of the marketing and design talking points is around this integrated sensor hub from both an engineering and end-user experience standpoint.

Note that Intel's Integrated Sensor Hub isn't new. The chip maker introduced the ISH with its Cherry Trail platform back in 2014 and [some laptops from Dell](https://www.dell.com/support/home/us/en/04/drivers/driversdetails?driverid=43ynt) and others already use it. However, I don't believe any Chrome OS device has had an ISH prior to this... or prior to Atlas, whenever it debuts, that is.

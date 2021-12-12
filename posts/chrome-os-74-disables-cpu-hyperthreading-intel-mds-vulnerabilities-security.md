---
title: "Chrome OS 74 disables CPU hyperthreading to mitigate Intel vulnerabilities"
date: "2019-05-14"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "chrome-os-74"
  - "google"
  - "intel"
  - "security"
coverImage: "Intel-Pentium-Silver-and-Celeron-chip.jpg"
---

If you've noticed your Chromebook performance to be a little slower with Chrome OS 74, it's could be due to a change in how your Chromebook handles CPU hyperthreading. More precisely, [Chrome OS 74 disables CPU hyperthreading to mitigate security risks due to Microarchitectural Data Sampling (MDS) vulnerabilities](https://support.google.com/faqs/answer/9330250).

Google has a Chrome OS support page with full details, but here's the key aspect:

> Microarchitectural Data Sampling (MDS) is a group of vulnerabilities that allow an attacker to potentially read sensitive data. If Chrome processes are attacked, these sensitive data could include website contents as well as passwords, credit card numbers, or cookies. The vulnerabilities can also be exploited to read host memory from inside a virtual machine, or for an Android App to read privileged process memory (e.g. keymaster).
> 
> To protect users, Chrome OS 74 disables Hyper-Threading by default. For the majority of our users, whose workflows are primarily interactive, this mitigates the security risk of MDS without a noticeable loss of responsiveness. Chrome OS 75 will contain additional mitigations.

If you want the details on MDS, you can read more about the vulnerabilities at their respective pages here:  [CVE-2018-12126](https://cve.mitre.org/cgi-bin/cvename.cgi?name=2018-12126), [CVE-2018-12127](https://cve.mitre.org/cgi-bin/cvename.cgi?name=2018-12127), [CVE-2018-12130](https://cve.mitre.org/cgi-bin/cvename.cgi?name=2018-12130), and [CVE-2019-11091](https://cve.mitre.org/cgi-bin/cvename.cgi?name=2019-11091). Keep in mind if you have an ARM processor in your Chromebook, you're not affected.

This kind of response, while unfortunate, is probably the best way to handle open vulnerabilities. And to be clear: They don't apply simply to Chromebooks: [They apply to any computer or device running on an Intel processor](https://www.intel.com/content/www/us/en/security-center/advisory/intel-sa-00233.html).

And frankly, while it may not be obvious to Chromebook device users if their machine is using hyperthreading for a particular use, typical usage likely doesn't take advantage of hyperthreading anyway. In which case, there's either a minimal or no impact.

While I don't recommend it, you can re-enable hyperthreading on your Chrome OS device by browsing to _chrome://flags#scheduler-configuration_ and enabling the "performance" setting.

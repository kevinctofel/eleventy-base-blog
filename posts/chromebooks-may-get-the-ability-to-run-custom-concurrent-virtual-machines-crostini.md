---
title: "Chromebooks may get the ability to run custom, concurrent VMs"
date: "2019-03-04"
categories: 
  - "news"
tags: 
  - "chrome-os"
  - "crostini"
  - "linux"
  - "project-crostini"
  - "virtual-machines"
coverImage: "Project-Crostini-Terminal-e1548790263160.png"
---

So let me preface this post to say that I'm not 100% sure what this will mean, but there's [direct evidence that Chromebooks will be able to run multiple virtual machines (VM), possibly at the same time](https://chromium-review.googlesource.com/c/chromiumos/platform2/+/1456441). Don't confuse VMs with Linux containers in this case: Crostini already supports multiple containers within a single VM, [which is the preferred method](https://www.reddit.com/r/Crostini/comments/8f2ty8/best_practice_multiple_vms_or_containers/).

Here's a code snippet indicating that this feature is coming and the title says it all:

![](https://i1.wp.com/www.aboutchromebooks.com/wp-content/uploads/2019/03/custom-concurrent-VMs-on-Chromebooks.png?fit=800%2C268&ssl=1)

Essentially as I understand it, the code change supports multiple listening ports between [Concierge in Chrome OS and Maitrde inside a VM](https://chromium.googlesource.com/chromiumos/docs/+/master/containers_and_vms.md#Overview) to execute commands securely. This could allow for multiple VMs to run at the same time and suggests that custom VMs will be supported. Currently in Crostini, [you have to use the Termina VM, which Google created, per the official Crostini docs](https://chromium.googlesource.com/chromiumos/docs/+/master/containers_and_vms.md#Can-I-run-my-own-VM_kernel):

![](https://i1.wp.com/www.aboutchromebooks.com/wp-content/uploads/2019/03/custom-vm-instead-of-Termina.png?fit=800%2C90&ssl=1)

Based on the code snippet, which clearly mentions a custom VM in the test results, it appears that other VMs will be allowed to run on a Chromebook. Does that mean you'll be able to install [VirtualBox](https://www.virtualbox.org/) or some other VM software, perhaps to run Windows or some other OS?

Frankly, I don't know and I can't tell with the limited information in the code commit. There's an associated bug with the change but it's only viewable internally by the Chromium team.

Clearly, though, the Chromium team wouldn't be modifying and then testing code for custom VMs for no good reason. And keep in mind that running a VM uses more hardware resources than running multiple Linux containers in[Crostini](https://www.aboutchromebooks.com/tag/project-crostini): These all use the same kernel and other hardware resources available to Chrome OS.

I'm sure there are plenty of readers smarter than me that can figure out the pros and cons of this change, as well as what it could enable on a Chromebook, so chime in the comments if you know!

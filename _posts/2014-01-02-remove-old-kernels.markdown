---
layout: post
title:  "Cleanup grub OS list"
date:   2014-01-02 21:30:26
categories: ubuntu tech
tags: quickfix ubuntu-kernel
---
Open terminal and check your current kernel:
`uname -r` 
`DO NOT REMOVE THIS KERNEL!`

Next, type the command below to view / list all installed kernels on your system.
`dpkg --list | grep linux-image`
Find all the kernels that lower than your current kernel. When you know which kernel to remove, continue below to remove it. Run the commands below to remove the kernel you selected.

`sudo apt-get purge linux-image-x.x.x.x-generic` 
Finally, run the commands below to update grub2

`sudo update-grub2`
Reboot your system.

[Reference](http://askubuntu.com/questions/2793/how-do-i-remove-or-hide-old-kernel-versions-to-clean-up-the-boot-menu)
-- Thanks to penreturn

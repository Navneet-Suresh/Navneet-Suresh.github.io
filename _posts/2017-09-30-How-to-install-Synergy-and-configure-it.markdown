---
layout: post
comments: true
title:  "How to control multiple PC with single application - Synergy Tutorial"
description: How to install Synergy on Multiple platforms - Windows & Linux for Free.
image: /assets/joao-silas-65013.jpg
author: N K I
---

<img class='responsive-image'
  src='/assets/media/joao-silas-65013.jpg' alt='How to Install Synergy - Post Image' >

# What is Synergy?

**Synergy** combines your desktop devices together in to one cohesive experience. It's software for sharing your mouse and keyboard between multiple computers on your desk. It works on Windows, macOS and Linux.(excerpt from Symless's Synergy Website)

**Synergy** is free and open source (free as in free speech),
meaning you are free to run it and redistribute it with
or without changes.
You can purchase their software if you want easy setup and want to support them

<div class="alert alert-success alert-dismissible fade show text-muted" role="alert">
 <h4 class="alert-heading">Offers:</h4>
 <p>If you want a VPS to run your blog or host your web-app,</p>
 <p>You should checkout Vultr.</p>
 <p><a href="https://www.vultr.com/?ref=7311876"><img class='responsive-image' src="https://www.vultr.com/media/banner_1.png"></a></p>
 <button type="button" class="close" data-dismiss="alert" aria-label="Close">
  <span aria-hidden="true">&times;</span>
 </button>
</div>

 **That sounds cool!, How to set it up?**
          Well that's what I am going to teach you in this blog post.
Sit tight.

## Steps to install Synergy on Multiple platforms.

1. Get your setup/source files from the above links.
2. If you are on Ubuntu (12.04 or UP) then follow the below steps.
3. Go to terminal **Ctrl + Alt + T**
4. Type sudo apt install synergy (works on Ubuntu 16.04) or you can compile it from **source**.
5. That's it.
6. For Windows & Other Unix based systems get the appropriate Installer.
7. Choose the **master computer**. The one which will act as a relay server between multiple devices. Once done open the Synergy app on that platform.
8. Then Choose Server option.
9. <img class='responsive-image' src='/assets/media/Synergy Setup.PNG' alt='Setup process synergy server' width='65%' weight='65%'>
10. <img class='responsive-image' src='/assets/media/Synergy Setup2.PNG' alt='Setup process synergy server' width='65%' weight='65%'>
11. Once configured start Synergy application on other desktops that you want to control.
12. Setup them as **Client** input the **IP addr (of the server)** .
13. And _viola_ setup is done.
14. Now you can easily use one keyboard and mouse over multiple PC's.

## Troubleshooting steps.

- Make sure the name of the desktop matches the screen name in server configuration
- If you want to make it a start-up app then you can create a startup script with help of startup manager on Ubuntu and You can do the same on Windows.


## Sources:

- Pre-built binaries: [Brahma-dev](https://github.com/brahma-dev/synergy-stable-builds)
- Source Code: [Synergy-Core](https://github.com/symless/synergy-core)
- Website: [symless.com](http://symless.com)
- Arch-Linux Wiki on Synergy: [Arch Linux Wiki](https://wiki.archlinux.org/index.php/synergy)
- Synergy Builds Official: [Official Builds](https://github.com/symless/synergy-core/releases)

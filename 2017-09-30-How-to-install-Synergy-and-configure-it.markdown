---
layout: default
title:  "How to install Synergy and configure it"
date:   2017-09-30 19:40:00
categories: main
---

<img 
  src='/assets/joao-silas-65013.jpg' alt='post image' width='65%' height='65%' >
  
What is Synergy?

Share one mouse and keyboard between multiple computers.

Synergy is free and open source (free as in free speech),
meaning you are free to run it and redistribute it with
or without changes.

Sources:

- Pre-built binaries: https://github.com/brahma-dev/synergy-stable-builds
- Source Code: https://github.com/symless/synergy-core
- Website: http://symless.com
- Arch-Linux Wiki on Synergy: https://wiki.archlinux.org/index.php/synergy
- Synergy Builds Official: https://github.com/symless/synergy-core/releases

 That sounds cool!, How to set it up?
          Well that's what I am going to teach you in this blog post.
Sit tight.

Steps to install Synergy on Multiple platforms.

- Get your setup/source files from the above links.
- If you are on Ubuntu (12.04 or UP) then follow the below steps.
- Go to terminal ctrl+alt + t
- type sudo apt install synergy
- that's it.
- For Windows get the appropriate Installer.
- For *nix systems do the same.
- Choose the master computer. The one which will act as a relay server between multiple devices. Once done open the Synergy app on that platform.
- Then Choose  Server option. </br>
- <img
  src='/assets/Synergy Setup.PNG' alt='Setup process synergy server' width='65%' weight='65%'> </br>
- <img
  src='/assets/Synergy Setup2.PNG' alt='Setup process synergy server' width='65%' weight='65%'> </br>
- Once configured start Synergy application on other desktops that you want to control.
- Setup them as Client input the IP addr (of the server) .
- And viola setup is done.
- Now you can easily use one keyboard and mouse over multiple PC's.

Troubleshooting steps.

- Make sure the name of the desktop matches he screen name in server configuration
- If you want to make it a startup app then you can create a startup script with help of startup manager on Ubuntu and You can do the same on Windows.
